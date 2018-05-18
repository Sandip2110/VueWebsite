<template>
  <footer class="container-fluid footer">
    <div class="row">
      <div class="col-sm-3" v-for="x in footerTableDetails"> 
        <FooterTable v-bind:footerTableHeading="x.title">
          <span slot="footerTableContent" v-html="x.content"> </span>
        </FooterTable>
      </div>
      <br>
    </div>
    
    <div class="text-center">
        <br><p>All Rights Reserved 2018 | Created with love by <a href="http://voidcanvas.com/" target="_blank"> VoidCanvas.com</a></p><br>
    </div>
  </footer>
</template>

<script>
import FooterTable from './FooterTable'
export default {
  name: 'Footer',
  components:{
    FooterTable,
  },
  data(){
    return{
      footerTableDetails:[{
        title:'About',
        content:'Smart Phone Zone is a smartphone dedicated website. Our valuable smartphone reviews help thousands of users to choose the perfect one for them.<br> Recently our mobile app development wing has been activated and we have successfully launched our first mobile app two weeks ago.'
      },
      {
        title:'Find Us',
        content:'<b>Address:</b> R.M.Road,Town Bardowali,Agartala,Tripura(W),<br><br><b>Ph:</b> +91 977483210/0381 2111111<br><b>Mail:</b>support@spz.com<br><br><b>Hours:</b> Mon-Fri (10Am to 5Pm)'
      },
      {
        title:"CEO's Words",
        content: 'Feel free to contact us for any kind of information, our team is always ready to help you.<br> If you want to join our team, you are heartly welcome! We prodive a great environment to work and learn the next level smartphone techs.<br>For further details please contact our HR team or you can mail to CEO.spz@spz.com.'
      },
      {
        title:'Career',
        content:'SPZ is proiding great career options for bloggers. If you are willing to be a part of our research, testing, technical or blogging team, send your CV today!<br>Send your updated resume to this email address, HR.spz@spz.com or you can directly upload it to our website.'

      }]
    }
  }
}
</script>

<style scopped>
.footer {
  background-color: #333333;
  color: #fff;
  padding: 5px;
  margin-top: 100px;
}
u {
  text-decoration-color:#0FBE7C
}
</style>


