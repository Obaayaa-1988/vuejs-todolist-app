<template>
  <div style="border: 1px solid; height: 500px; padding: 5rem">
    <InputField
      :placeholder="'enter a letter or number'"
      :color="'5px solid blue'"
    />
    <br />
    <InputField
      :placeholder="'Enter your name here'"
      :color="'5px solid black'"
    />
    <br />
    <InputField
      :placeholder="'Enter your address here'"
      :color="'5px solid green'"
    />
    <br />
    <InputField
      :color="'5px solid red'"
      :placeholder="'Enter your address here'"
    />
    <br />
    <InputField
      :placeholder="'Enter your location here'"
      :color="'5px solid purple'"
    />
    <br />
    <InputField
      :placeholder="'Enter your job here'"
      :color="'5px solid yellow'"
    />
    <br />
    <InputField
      :placeholder="'Enter your country here'"
      :color="'5px solid pink'"
    />
    <br />
    <InputField
      :placeholder="'Enter your business here'"
      :color="'5px solid brown'"
    />
    <br />
    <InputField
      :placeholder="'Enter your church here'"
      :color="'5px solid cyan'"
    />
    <br />
    <button id="btn">send</button>
  </div>
</template>

<script>
// import InputField from "./components/InputField.vue";
import InputField from "./InputField.vue";

export default {
  name: "HelloWorld",
  components: {
    InputField,
  },
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#btn {
  padding: 10px;
  border: none;
  background-color: tomato;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
