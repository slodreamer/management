<style scoped>
    .layout{
        border: 1px solid #d7dde4;
        background: #f5f7f9;
        position: relative;
    }
    .layout-breadcrumb{
        padding: 10px 15px 0;
    }
    .layout-content{
      position: absolute;
      right: 0px;
      left: 0;
      top: 44px;
      bottom: 40px;
      border: 1px solid #f00;
    }
    .layout-content-main{
        padding: 10px;
    }
    .layout-copy{
      text-align: center;
      color: #676a6c;
      position: fixed;
      bottom: 0;
      margin: 0;
      padding: 10px 0;
      right: 0;
      left: 18%;
      font-size: 13px;
      background: #F5F5F5;
      border-top: 1px solid #e7eaec;
      font-weight: 500;
    }
    .layout-menu-left{
        background: #464c5b;
        position: fixed;
        height: 100%;
        /* overflow-y: auto; */
        width: 18%;
    }
    .layout-header{
        height: 60px;
        background: #fff;
        box-shadow: 0 1px 1px rgba(0,0,0,.1);
    }
    .layout-logo-left{
        width: 90%;
        height: 30px;
        background: #5b6270;
        border-radius: 3px;
        margin: 15px auto;
    }
    .gome-layout .ivu-col-span-19 {
      position: absolute;
      left: 18%;
      right: 0;
      width: 82%;
    }
    .layout-breadcrumb {
      padding: 10px 0;
      position: fixed;
      right: 0;
      left: 18%;
      border: 1px solid #ccc;
    }
</style>
<template>
    <div class="layout gome-layout">
        <Row type="flex">
            <i-col span="5" class="layout-menu-left">
                <Menu active-name="1-2" theme="dark" width="auto" :open-names="['1']">
                    <div class="layout-logo-left"></div>
                    <Submenu name="1">
                        <template slot="title">
                            <Icon type="ios-navigate"></Icon>
                            导航一
                        </template>
                        <Menu-item name="1-1">选项 1</Menu-item>
                        <Menu-item name="1-2">选项 2</Menu-item>
                        <Menu-item name="1-3">选项 3</Menu-item>
                    </Submenu>
                    <Submenu name="2">
                        <template slot="title">
                            <Icon type="ios-keypad"></Icon>
                            导航二
                        </template>
                        <Menu-item name="2-1">选项 1</Menu-item>
                        <Menu-item name="2-2">选项 2</Menu-item>
                    </Submenu>
                    <Submenu name="3">
                        <template slot="title">
                            <Icon type="ios-analytics"></Icon>
                            导航三
                        </template>
                        <Menu-item name="3-1">选项 1</Menu-item>
                        <Menu-item name="3-2">选项 2</Menu-item>
                    </Submenu>
                    <Submenu name="3">
                        <template slot="title">
                            <Icon type="ios-analytics"></Icon>
                            导航三
                        </template>
                        <Menu-item name="3-1">选项 1</Menu-item>
                        <Menu-item name="3-2">选项 2</Menu-item>
                    </Submenu>
                    <Submenu name="3">
                        <template slot="title">
                            <Icon type="ios-analytics"></Icon>
                            导航三
                        </template>
                        <Menu-item name="3-1">选项 1</Menu-item>
                        <Menu-item name="3-2">选项 2</Menu-item>
                    </Submenu>
                    <Submenu name="3">
                        <template slot="title">
                            <Icon type="ios-analytics"></Icon>
                            导航三
                        </template>
                        <Menu-item name="3-1">选项 1</Menu-item>
                        <Menu-item name="3-2">选项 2</Menu-item>
                    </Submenu>
                </Menu>
            </i-col>
            <i-col span="19">
                <div class="layout-breadcrumb">
                    <Breadcrumb>
                        <Breadcrumb-item href="#">首页</Breadcrumb-item>
                        <Breadcrumb-item href="#">应用中心</Breadcrumb-item>
                        <Breadcrumb-item>某应用</Breadcrumb-item>
                    </Breadcrumb>
                </div>
                <div class="layout-content">
                    <div>内容区域</div>
                    <!-- <iframe src="https://cn.vuejs.org/" frameborder="0" width="100%" height="100%"></iframe> -->
                </div>
                <div class="layout-copy">
                    © 2015-2016 United States and the United States the official website of the letter Network Technology Co. Ltd. all rights reserved ICP 15012739
                </div>
            </i-col>
        </Row>
    </div>
</template>
<script>
    export default {    
    }
</script>