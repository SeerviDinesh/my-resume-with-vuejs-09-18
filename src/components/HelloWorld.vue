<template>
  <div class="hello">
    <div class="row">
      <div class="col-sm-8 border border-primary padding-left text-left">
        <h1> {{restitle}} </h1>
        <h3> {{web}} </h3>
      </div>
      <div class="col-sm-4 border border-primary text-left">
          <div class="fa fa-phone icon1"> &nbsp;&nbsp;
            {{phone}}
          </div> <br>
          <div class="fa fa-map-marker"> &nbsp;&nbsp;
            {{address}}
          </div><br>
          <div  class="fa fa-map-marker">&nbsp;&nbsp;
            {{email}}
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      restitle: 'DINESH SEERVI',
      phone: '+91-7877613144',
      web: 'Web Developer',
      address: 'Bilara, Jodhpur (Raj.)',
      email: 'crvidinesh@gmail.com'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-weight: bold;
  color: steelblue;
  font-size: 60px;
}
h3 {
  color:grey;
}
.hello {
  padding-left: 50px;
  padding-right: 50px;
  margin-top: 50px;
}
</style>
