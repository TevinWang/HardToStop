<template>
  <div id="home">
    <b-jumbotron
      header="hard to stop."
      class="hero ml-5 mr-5 mt-2 mb-2 text-center"
      lead="Addiction could be fatal. We need to help those addicted to find treatment."
    >
      <p>
        Many people fall into the trap of taking drugs--whether it is an
        environment of peer pressure, or the promotion of drugs in the media.
        Once taken, drugs can create a cycle of use that leads to addiction, and
        unfortunately fatal symptoms. It is important that people help family
        and friends overcome their drug addictions and to seek help.
      </p>
      <b-container>
        <b-row aligh-h="end">
          <b-col>
            <img width=100%  src="https://assets.donordrive.com/Shatterproof/images/logoImage.png" />
            
          </b-col>
          <b-col>
            <img width=100% src="https://www.samhsa.gov/sites/default/files/png_270_kb.png" />
        
           </b-col>
          
        </b-row>
        <b-row>
         <b-col><b-button variant="dark" href="https://shatterproof.org/">Join Shatterproof</b-button></b-col>
         <b-col><b-button variant="dark" href="https://www.samhsa.gov/find-help/national-helpline">View Helpline</b-button></b-col>
         </b-row>
      </b-container>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: "Hero",
  // props: {
  //   msg: String
  // }
};
</script>

<style scoped>
.hero {
  background-image: src(
    "https://hhp-blog.s3.amazonaws.com/2020/06/GettyImages-823854648-scaled.jpg"
  );
  background-size: cover;
  height: 100%;
}
</style>