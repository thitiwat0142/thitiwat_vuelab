<template>
  <div style="text-align: center">
    <ul v-for="Contracts in Contract" :key="Contracts.id">
      <li>
        {{ Contracts.id }}
        {{ Contracts.Name }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data: () => ({
    Contract: [
      {
        id: "Contract : ",
        Name: "กม25 ซอยกู้เกียรติ์ 2 พหลโยธิน 10220 กรุงเทพมหานคร",
      },
      { id: "Email :", Name: "thitiwat.ka@ku.th" },
      { id: "Phone :", Name: "0954938986" },
    ],
  }),
};
</script>