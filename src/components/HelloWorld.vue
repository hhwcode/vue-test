<template>
    <div>
      <el-row>hello vue</el-row>
      <el-row>
        <el-col :span="8">
            <el-input v-model="input" placeholder="请输入内容"></el-input>
            <div>{{input}}</div>
        </el-col>
      </el-row>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      input: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
