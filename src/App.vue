<template>
  <div id="app">
    <layout>
        <div slot="header">
          게시판 CRUD
        </div>

        <div slot="nav">
          <ul>
            <li>
              <router-link to="/post/write">게시물 등록</router-link>
            </li>
            <li>
              <router-link to="/post/list">게시물 리스트</router-link>\
            </li>
          </ul>
        </div>
    </layout>
  </div>
</template>

<script>
import Layout from './components/layout/Layout.vue'

export default {
  components: {
    Layout
  }
}
</script>
