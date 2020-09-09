<template>
  <div class="choice">
      <h1>เลือกแนวทางการช่วยเหลือของคุณ</h1>
      <h2>เลือกช่วยได้เท่าที่ไหว</h2>
      <div class="image">
        <div class="share-land">
          <img src="../assets/choice1.png" alt="" style="width:200px; height:200px;">
          <h4>แบ่งปันพื้นที่</h4>
        </div>
        <div class="watch-ads">
          <img src="../assets/choice2.png" alt="" style="width:200px; height:200px;">
          <h4>ปลูกต้นไม้</h4>
        </div>
        <div class="volunteer">
          <router-link to="Plant"></router-link>
        <img src="../assets/choice3.png" alt="" style="width:200px; height:200px;">
        <h4>ร่วมเป็นอาสาสมัคร</h4>
      </div>
      </div>
  </div>
</template>

<script>
export default {
  data:function(){
    return{

    }
  }
}
</script>

<style>
.choice{
  padding-top:5rem;
  padding-bottom:10rem;
}
.image{
  margin-top:5rem;
  display:flex;
  justify-content: space-around;
}
.share-land:hover{
  background-color: rgb(94, 189, 94);
  color:white;
}
.watch-ads:hover{
  background-color: rgb(94, 189, 94);
  color:white;
}
.volunteer:hover{
  background-color: rgb(94, 189, 94);
  color:white;
}
</style>