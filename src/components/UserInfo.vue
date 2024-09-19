<template>
  <div>
    <h2>B5</h2>
   <ul><h2>Thong tin nguoi dung</h2>
   <li>Ho va ten: {{user.userName}}</li>
   <li>Gioi tinh: {{user.gender}}</li>
   <li>Ngay sinh: {{user.birth}}</li>
   <li>Email: {{user.email}}</li>
    <li>Dia chi: {{user.address}}</li>
    </ul> 
  </div>
</template>

<script>
export default {
    data(){
        return {
            user:{
                    userName:"Le Dien Tien",
                    gender:"Nam",
                    birth:"28/07/2005",
                    email:"ledientien2005@gmail.com",
                    address:"Thanh Xuan, Ha Noi",
            }
        }
    }
}
</script>

<style>

</style>