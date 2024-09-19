<template>
  <div>
    <h1>Thông tin cá nhân</h1>
    <ul>
      <li>
        Họ và tên: <b>{{ personalInfo.fullName }}</b>
      </li>
      <li>
        Giới tính: <b>{{ personalInfo.gender }}</b>
      </li>
      <li>
        Ngày sinh: <b>{{ personalInfo.dob }}</b>
      </li>
      <li>
        Email: <b>{{ personalInfo.email }}</b>
      </li>
      <li>
        Địa chỉ: <b>{{ personalInfo.address }}</b>
      </li>
    </ul>
  </div>
</template>

<script setup>
const personalInfo = {
  fullName: "ntc",
  gender: "Nam",
  dob: "04/06/2004",
  email: "ntc2507@gmail.com",
  address: "hp, Hà Nội",
};
</script>

<style></style>
