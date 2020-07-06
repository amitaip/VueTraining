<template>
    <table>
        <tr>
            <td><p>First Name: </p></td>
            <td><input type="text" v-model="firstName" placeholder="type your first name"/></td>
        </tr>
        <tr>
            <td><p>Last Name: </p></td>
            <td><input type="text" v-model="lastName" placeholder="type your last name"/></td>
        </tr>
        <tr>
            <td><p>Email: </p></td>
            <td><input type="email" v-model="eMail" placeholder="type your email address"/></td>
        </tr>
    </table>
</template>

<script>
    export default {
        name: 'Register',
        data() {
            return {
                firstName: '',
                lastName: '',
                eMail: ''
            }
        }
    };
</script>

<style scoped>

</style>

