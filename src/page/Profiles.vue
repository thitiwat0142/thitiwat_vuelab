<template>
  <div style="text-align: center">
    <ul v-for="profile in profiles" :key="profile.id">
      <li>
        <button>
          {{ profile.id }}
          {{ profile.Title }}
        </button>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data: () => ({
    profiles: [
      { id: "NAME :", Title: "Thitiwat Kahanet" },
      { id: "AGE : ", Title: " 20" },
      { id: "SKILL :", Title: " C C+ Java SQL/PL " },
    ],
  }),
};
</script>