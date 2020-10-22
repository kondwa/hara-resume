<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      A Seasoned Computer Engineer with all around system knowledge in High Speed Computing platform, Development, Scripting and Networking.
    </p>
    <h3>Academic Qualification</h3>
    <ul>
      <li>Master of Science @ Mzuzu University in 2009</li>
      <li>Bachelor of Science @ Chancellor College in 2006</li>
    </ul>
    <h3>Professional Experience</h3>
    <ul>
      <li>Systems Administrator and Developer @ mHub, July 2020 - Present.</li>
      <li>Software Engineer @ Malswitch, July 2015 - February 2016</li>
      <li>Senior Software Developer @ Baobab Health Trust, April 2009 - September 2009</li>
      <li>Senior Systems Engineer @ UltiNets, January 2008 - January 2009</li>
      <li>Systems Developer @ Epsilon & Omega, February 2006 - March 2007</li>
    </ul>
    <h3>Skills</h3>
    <ul>
      <li>Software Development</li>
      <li>Network Engineering</li>
      <li>Systems Administration</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Resume',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
