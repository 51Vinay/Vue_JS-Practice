<template>
    <div>
        <h1>Home Componenet</h1>
        <h2>Email: {{ email }}</h2>
        <h2>Phone:{{ phone }}</h2>
    </div>
</template>
<script>
export default{
    name:'HomeComponent',
    data(){
        return{
            email:"abc@gmail.com",
            phone:"7867564534"
        }
    }
}
</script>