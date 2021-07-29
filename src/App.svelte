<script>
  import home from './assets/home.png'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <p class="head-word">#สาจุเลิกสั่งงาน#รรย่านมิดทาว</p>
  <div style="text-align: center;">
  <p style="font-size: 3vw; text-align: center;">REPORT ปัญหาต่างๆในการเรียน</p>
  <p style="text-align: center;">หากมีปัญหาสามารถส่งมาได้ที่ <a href="https://docs.google.com/forms/d/e/1FAIpQLSfXv8Ot3Va7EQ2cxnEMOllpsBeO9gtBW4lcsEoLGiNtg8pM-A/viewform?usp=sf_link" target="_blank">Google form</a> </p>
  <p>กรุณาเลือกปัญหาที่อยากดู</p>
  <p><a href="#online problem">การเรียนออนไลน์</a> | <a href="#onsite">การเรียนออนไซต์</a> | <a href="#test">การสอบ</a> | <a href="#homework">การบ้าน</a> | <a href="#life">การใช้ชีวิต</a> | <a href="#other">อื่นๆ</a></p>
  </div>
  <div class="hh" id="online problem">
  <div class="left-box">
    <h1>การเรียนออนไลน์</h1>
  </div>
  </div> 

  <div class="hh" id="onsite">
    <div class="left-box">
      <h1>การเรียนออนไซต์</h1>
    </div>
    </div> 

    <div class="hh" id="test">
      <div class="left-box">
        <h1>การสอบ</h1>
      </div>
      </div> 

      <div class="hh" id="homework">
        <div class="left-box">
          <h1>การบ้าน</h1>
        </div>
        </div> 

        <div class="hh" id="life">
          <div class="left-box">
            <h1>การใช้ชีวิต</h1>
          </div>
          </div> 
        
          <div class="hh" id="other">
            <div class="left-box">
              <h1>อื่นๆ</h1>
            </div>
            </div> 




</main>

<style>

  @font-face {
    font-family: "Anakotmai";
    font-style: normal;
    font-weight: normal;
    src: url("../public/fonts/anakotmai/anakotmai-medium.eot"); /* IE9 Compat Modes */
    src: url("../public/fonts/anakotmai/anakotmai-medium.eot#iefix")
        format("embedded-opentype"),
      url("../public/fonts/anakotmai/anakotmai-medium.woff2") format("woff2"),
      url("../public/fonts/anakotmai/anakotmai-medium.woff") format("woff");
  }
  @font-face {
    font-family: "Anakotmai";
    font-style: normal;
    font-weight: bold;
    src: url("../public/fonts/anakotmai/anakotmai-bold.eot"); /* IE9 Compat Modes */
    src: url("../public/fonts/anakotmai/anakotmai-bold.eot#iefix")
        format("embedded-opentype"),
      url("../public/fonts/anakotmai/anakotmai-bold.woff2") format("woff2"),
      url("../public/fonts/anakotmai/anakotmai-bold.woff") format("woff");
  }
  @font-face {
    font-family: "Anakotmai";
    font-style: normal;
    font-weight: 300;
    src: url("../public/fonts/anakotmai/anakotmai-light.eot"); /* IE9 Compat Modes */
    src: url("../public/fonts/anakotmai/anakotmai-light.eot#iefix")
        format("embedded-opentype"),
      url("../public/fonts/anakotmai/anakotmai-light.woff2") format("woff2"),
      url("../public/fonts/anakotmai/anakotmai-light.woff") format("woff");
  }
  * {
    font-family: "Anakotmai", -apple-system, BlinkMacSystemFont, "Segoe UI",
      Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue",
      sans-serif;
      line-height: 1.1;
    margin: 2rem auto;

  }

  a{
    color: rgb(49, 48, 48);
    text-decoration: blue;
  }
  .head-word{
    font-weight: 500;
    font-size: 7vw;
    text-align: center;
    margin-top: -10px;
  }
  .left-box{
    margin-left: 100px;
    height: 250px;
    width: 500px;
    border: 3px solid grey;
    text-align: center;
    flex: 50%;
    margin-right: 100px;
  }
  .hh{
    display: flex;
  flex-wrap: wrap;

  text-align: center;
  }


</style>
