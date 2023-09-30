<template>
  <div>
    <el-row>

      <el-col :span="12">
        <div style="width: 100%; height: 300px; background-color: dodgerblue"></div>
      </el-col>

      <el-col :span="12">
        <div style="width: 100%; height: 300px; background-color: red"></div>
      </el-col>

    </el-row>

    <el-row>
      <el-col :span="6"><img style="width: 100%" src="@/assets/logo.png" alt=""></el-col>
      <el-col :span="6"><img style="width: 100%" src="@/assets/logo.png" alt=""></el-col>
      <el-col :span="6"><img style="width: 100%" src="@/assets/logo.png" alt=""></el-col>
      <el-col :span="6"><img style="width: 100%" src="@/assets/logo.png" alt=""></el-col>

    </el-row>

    <el-row>
      <el-col span="24">
        <button>按钮</button>
        <el-button>Element的按钮</el-button>
        <el-button type="primary">主要的按钮</el-button>
        <el-button type="danger">危险的按钮</el-button>
        <el-button type="warning">警告的按钮</el-button>
        <el-button type="success">成功的按钮</el-button>
      </el-col>

    </el-row>

    <el-row style="margin-top: 20px">
      <el-col>
        <el-input style="width: 200px" v-model="value" placeholder="请输入"></el-input>
        <el-input show-password style="width: 200px" v-model="password" placeholder="请输入密码"></el-input>
      </el-col>

    </el-row>



  </div>
</template>

<script>
export default {
  name: 'Element',
  data() {
    return {
      value: '',
      password: '',
    }
  }
}
</script>