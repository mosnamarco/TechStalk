<script setup>
</script>

<template>
  <main>
    <h3>Results</h3>

    <div class="container">
      <div class="profile_pic_preview">
        <h3>Profile Preview</h3>
        <img src="https://randomuser.me/api/portraits/women/70.jpg" alt="">
      </div>

      <div class="content">
        <table>
          <tr>
            <th>Facebook Link</th>
            <th>Email</th>
            <th>Phone Number</th>
          </tr>
          <tr>
            <th>facebook.com/sample</th>
            <th>something@gmial.copm</th>
            <th>+9839123388232938</th>
          </tr>
          <tr>
            <th>facebook.com/sample</th>
            <th>something@gmial.copm</th>
            <th>+9839123388232938</th>
          </tr>
          <tr>
            <th>facebook.com/sample</th>
            <th>something@gmial.copm</th>
            <th>+9839123388232938</th>
          </tr>
          <tr>
            <th>facebook.com/sample</th>
            <th>something@gmial.copm</th>
            <th>+9839123388232938</th>
          </tr>
          
          <tr>
            <th>facebook.com/sample</th>
            <th>something@gmial.copm</th>
            <th>+9839123388232938</th>
          </tr>
          <tr>
            <th>facebook.com/sample</th>
            <th>something@gmial.copm</th>
            <th>+9839123388232938</th>
          </tr>
          <tr>
            <th>facebook.com/sample</th>
            <th>something@gmial.copm</th>
            <th>+9839123388232938</th>
          </tr>
          <tr>
            <th>facebook.com/sample</th>
            <th>something@gmial.copm</th>
            <th>+9839123388232938</th>
          </tr>
        </table>
      </div>
    </div>
  </main>
</template>

<style scoped>
main {
  color: white;
  padding-top: 20px;
  display: flex;
  align-items: center;
  vertical-align: center;
  flex-direction: column;
}
h3 {
  margin: 20px;
}
table {
  border-spacing: 30px;
}
.container {
  display: flex;
  justify-content: center;
  flex-direction: row;
  gap: 50px;
}
.profile_pic_preview {
  text-align: center;
  max-height: max-content;
}
.profile_pic_preview img {
  min-width: 250px;
}
</style>
