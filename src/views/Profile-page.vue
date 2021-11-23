<template>
<div id="n">
    <div class="tab">
        <img src="../assets/logo.png" alt="Profile Picture">
        <h3>Name</h3>
        <form action="" method="get"> 
            <div class="input">
                <label for="fullName">Name : </label>
                <input type="text" name="fullName" id="fullName" value="John" disabled>
            </div>
            <div class="input">
                <label for="dateOfBirth">Date of birth : </label>
                <input type="text" name="dateOfBirth" id="dateOfBirth" value="01/01/2021" disabled>
            </div>
            <div class="input">
                <label for="email">Email : </label>
                <input type="text" name="email" id="email" value="abcde@xyz.com" disabled>
            </div>
            <div class="input">
                <label for="sex">Sex : </label>
                <input type="text" name="sex" id="" value="Male" disabled>
            </div>
            <div class="input">
                <label for="phoneNumber">Phone Number : </label>
                <input type="text" name="phoneNumber" id="phoneNumber" value="+234812341212" disabled>
            </div>
            <div class="input">
                <label for="staffNumber">Staff Number : </label>
                <input type="text" name="staffNumber" id="staffNumber" value="123abcd" disabled>
            </div>
            <div class="input">
                <label for="address">Address : </label>
                <input type="text" name="address" id="address" value="No. 123 street, Lagos" disabled>
            </div>
            <div class="input">
                <label for="stateOfOrigin">State of Origin : </label>
                <input type="text" name="stateOfOrigin" id="stateOfOrigin" value="Delta" disabled>
            </div>
            <div class="input">
                <label for="position">Position : </label>
                <input type="text" name="position" id="position" value="Teacher" disabled>
            </div>
            <div class="input">
                <label for="specialization">Specialization : </label>
                <input type="text" name="specialization" id="specialization" value="Computer" disabled>
            </div>
            <div class="input">
                <label for="nationality">Nationanlity : </label>
                <input type="text" name="nationality" id="" value="Nigerian" disabled>
            </div>
            <div class="input">
                <label for="status">Status : </label>
                <input type="text" name="status" id="" value="Active" disabled>
            </div>
            <input type="button" id="save" value="Save">
            <input type="button" id="edit" value="Edit">
            <!-- disabled -->
            
        </form>
    </div>
    <div class="tab">
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                Est voluptate labore eius eaque asperiores expedita magni aliquid quod! 
                Unde corrupti inventore quaerat assumenda sint, 
                excepturi voluptates vel iste id quia iusto laborum itaque mollitia cum 
                ut nisi maiores perspiciatis ipsa praesentium sunt illo debitis earum animi. 
                Reprehenderit quos maxime labore?</p>
       
    </div>
</div>
</template>

<script>

export default {

}



        let disableKey = ()=>{
            console.log(document.getElementsByTagName('input'));
            for (let index = 0; index < document.getElementsByTagName('input').length; index++) {
                document.getElementsByTagName('input')[index].removeAttribute('disabled') ;
            }
            document.getElementsByTagName('input')[11].setAttribute('disabled','disabled');
            document.getElementsByTagName('input')[2].setAttribute('disabled','disabled');
            document.getElementsByTagName('input')[5].setAttribute('disabled','disabled');
        }

        let enableKey = ()=>{
            console.log(document.getElementsByTagName('input').length);
            for (let index = 0; index < document.getElementsByTagName('input').length; index++) {
                document.getElementsByTagName('input')[index].setAttribute('disabled','disabled');
            }
            document.getElementsByTagName('input')[13].removeAttribute('disabled')
        }

        document.getElementById('edit').addEventListener('click', disableKey)
        document.getElementById('save').addEventListener('click', enableKey)

</script>

<style scoped>
 body{
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    input {
        display: inline;
        padding: 5%;
    }
    .input {
        display: block;
        padding: 5%;
    }
    label {
        display: inline;
    }
    #n {
        display: flex;
        align-items: center;
        width: 80%;
    }
    .tab {
        padding: 3%;
    }
</style>
