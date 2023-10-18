<template>
  <div>
    <h1>ABOUT ME</h1>
    <div class="about">
      <p>Name:</p><h3> {{ user.name }}</h3>
    </div>
    <div class="about">
      <p>Surname:</p><h3> {{ user.surname }}</h3>
    </div>
    <div class="about">
      <p>Code:</p><h3> {{ user.code }}</h3>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        name: "Marks",
        surname: "Cimermanis",
        code: "IT21060",
      },
    };
  },
};
</script>
