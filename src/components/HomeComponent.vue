<template>
    <div>
        <h1>Home Componenet</h1>
        <h2>Email: {{ email }}</h2>
        <h2>Phone:{{ phone }}</h2>
        <h2>Name:{{ getName("Vinay") }}</h2>
        <h2>Old Data :{{ getData() }}</h2>
    </div>
</template>
<script>
export default{
    name:'HomeComponent',
    data(){
        return{
            email:"abcd@gmail.com",
            phone:"7867564534"
        }
    },
    methods:{
        getName(name)
        {
            return name;
        },
        getData(){
            return {
                Name:"abc",
                email: this.email
            }
        }

    }
}
</script>