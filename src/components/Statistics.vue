<template class="cont">
  <div id="statistics">
    <h1 class="text-center">Statistics</h1>
    <hr />
    <vue-aos animation-class="fadeIn animated">
    <b-row align-v="center">
      
      <b-col class="p-2" col md="4">
        <h1 class="display-1 text-right">88000</h1>
      </b-col >
      <b-col class="p-2" col md="8">
        <h3 class="text-left align-center">overdose deaths during the COVID19 pandemic</h3>
      </b-col> 
    </b-row>
     </vue-aos>
     <b-row align-v="center">
       <b-col class="p-2" col md="8">
        <h3 class="text-right align-center">an increase in deaths from the previous year of</h3>
      </b-col>
      <b-col class="p-2" col md="4">
        <h1 class="display-1 text-left">27%</h1>
      </b-col >
    </b-row>
    <b-row align-v="center">
      <b-col class="p-2" col md="4">
        <h1 class="display-1 text-right">740 BILLION</h1>
      </b-col >
      <b-col class="p-2" col md="8">
        <h3 class="text-left align-center">lost in workplace productivity, healthcare expenses, and crime-related costs. </h3>
      </b-col>
    </b-row>
     <b-row align-v="center">
       <b-col class="p-2" col md="8">
        <h3 class="text-right align-center">American adults that battled a substance use disorder in 2017:</h3>
      </b-col>
      <b-col class="p-2" col md="4">
        <h1 class="display-1 text-left">19.7 MILLION</h1>
      </b-col >
    </b-row>
  </div>
</template>

<script>
export default {
  name: "Statistics",
  // props: {
  //   msg: String
  // }
};
</script>

<style>
.cont {
  text-align: center !important;
  margin: 20px;
}
</style>