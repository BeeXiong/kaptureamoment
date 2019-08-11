<template>
  <div id="aboutUsContent">
    <div class="thisThing">
      <div>
        <h1>Our Plan</h1>
      </div>
      <div>
        <h3>Wedding photographers do an amazing job recording traditional shots that every couple should have.  However, there are candid and spontaneous moments that occur and we want to help with those moments. </h3>
        <h4>A reunion of college roommates who haven’t seen each other for a few years. </h4>
        <h4>Your best friends from different cities meeting for the first time.</h4>
        <h4>Your families who have traveled great distances to spend the special day with you.</h4>
        <h3>Our Service and Software will help to kaptureamoment and allow everyone to show why the wedding was memorable for them.</h3>
      </div>
    </div>
    <div class="c">
      <div class="cFrame">
        <img class="cPic" src="../assets/IMG_1071.jpg">
        <div class="stories">
          <h2>Some Fried Chicken</h2>
          <h4>Not very many people saw this but the combination of a long travel day, no dinner and cocktails led to this amazing moment. The untouched piece of chicken leftover from the rehearsal dinner became this couple’s couples dinner. Very few saw it but this memory can now be remembered by many.</h4>
        </div>
      </div>
    </div>
      <div class="m">
        <div class="cFrame">
          <img class="cPic" src="../assets/IMG_1216.jpg">
          <div class="stories">
            <h2>A First Dance</h2>
            <h4>Table 7 got the best seat in the house for the first dance. A few drinks, a white rose, a “Book of Love” and the happy couple gave us this view. We got the chance to see our friends, our co-workers and for many of us, our roommates enjoy their special day.</h4>
          </div>
        </div>
      </div>
    <div class="y">
      <div class="cFrame">
        <img class="cPic" src="../assets/tidePen.jpg">
        <div class="stories">
          <h2>The Tide Pen</h2>
          <h4>On our first day of football practice in college, our coach told us to look around because you may see someone who would be in your wedding. Turns out he was right. This moment wasn’t just about using the tide pen at our friend's wedding. It was about those words and how true they were.</h4>
        </div>
      </div>
    </div>
  </div>

</template>

<script>
export default {

  data () {
    return {

    }
  }
}
</script>

<style lang="scss">

#aboutUsContent{
  min-width: 350px;
  height:1200px;
}

@media(max-height: 800px){

  #aboutUsContent .c{
    width:82%;
    height: 19%;
    background: linear-gradient(0deg, #009FDF 100%, #ffffff 50%) no-repeat;
    margin: 40px 0 0 20%;
  }
  #aboutUsContent .m{
    width:82%;
    height: 19%;
    background: linear-gradient(0deg, #D6006E 100%, #ffffff 50%) no-repeat;
    margin: 250px 0 0 20%;
  }
  #aboutUsContent .y{
    width:82%;
    height: 19%;
    background: linear-gradient(0deg, #FFFF00 100%, #ffffff 50%) no-repeat;
    margin: 250px 0 0 20%;
  }

  .thisThing{
    width:95%;
    height: auto;
    margin:0;
    text-align: left;
    padding:10px;
  }
  .thisThing h1{
    color: #000;
  }
  h2,h3{
    color: #000;
  }
  .y h3{
    color: #fff;
  }

  .cPic{
   width:250px;
   height: 250px;
   margin: -5% -23%;
   border-radius: 500px;
   box-shadow: 5px 3px 12px -4px #4d4d4d, -1px 1px 2px -2px #4d4d4d;
   border: solid 6px #fff;
  }
  .cFrame{
    width:100%;
    height: 100%;
    margin:5px,0;
  }
  .stories{
    width: 95%;
    height:auto;
    margin: 0 auto 0 -20%;
  }
}
@media(min-width : 801px) and (max-width : 1149px) {
  #aboutUsContent .c{
    width:86%;
    height: 20%;;
    background: linear-gradient(52deg, #009FDF 78%, #ffffff 50%) no-repeat;
    margin: 75px 0 0 15%;
  }
  #aboutUsContent .m{
    width:86%;
    height: 20%;
    background: linear-gradient(52deg, #D6006E 78%, #ffffff 50%) no-repeat;
    margin: 75px 0 0 15%;
  }
  #aboutUsContent .y{
    width:86%;
    height: 20%;
    background: linear-gradient(52deg, #FFFF00 78%, #ffffff 50%) no-repeat;
    margin: 75px 0 0 15%;
  }

  .thisThing{
    width:100%;
    height:300px;
    margin:0 auto;
    text-align: left;
  }
  .thisThing h1{
    color: #000;
  }
  .thisThing h4{
    color: #000;
  }
  h2, h4{
    color: #fff;
  }
  .y h2{
    color:#000;
  }
  .y h4{
    color:#000;
  }
  .cPic{
   width:250px;
   height: 250px;
   margin: -4% 3%;
   border-radius: 500px;
   box-shadow: 5px 3px 12px -4px #4d4d4d, -1px 1px 2px -2px #4d4d4d;
   border: solid 6px #fff;
  }
  .cFrame{
    width:95%;
    height: 100%;
    margin:2% -18%;
    display: inline-flex;
  }
  .stories{
    margin: -2% auto;
  }
}
@media(min-width : 1150px) {
  #aboutUsContent .c{
    width:68%;
    height: 20%;;
    background: linear-gradient(45deg, #009FDF 73%, #ffffff 50%) no-repeat;
    margin: 75px 0 0 35%;
  }
  #aboutUsContent .m{
    width:68%;
    height: 20%;
    background: linear-gradient(45deg, #D6006E 73%, #ffffff 50%) no-repeat;
    margin: 75px 0 0 35%;
  }
  #aboutUsContent .y{
    width:68%;
    height: 20%;
    background: linear-gradient(45deg, #FFFF00 73%, #ffffff 50%) no-repeat;
    margin: 75px 0 0 35%;
  }

  .thisThing{
    width:23%;
    height:600px;
    position: absolute;
    margin:0 25px;
    text-align: left;
  }
  .thisThing h1{
    color: white;
    font-size: 40px;
  }
  h2, h3, h4{
    color: #fff;
  }
  .y h2{
    color:#000;
  }
  .y h4{
    color:#000;
  }

  .cPic{
   width:250px;
   height: auto;
   margin: -4.6% 10px 0 7.5%;
   border-radius: 50%;
   box-shadow: 5px 3px 12px -4px #4d4d4d, -1px 1px 2px -2px #4d4d4d;
   border: solid 6px #fff;
  }

  .cFrame{
    width:90%;
    height: 100%;
    margin:30px -19%;
    display: inline-flex;
  }
  .stories{
    margin: -2% auto;
  }
}
</style>
