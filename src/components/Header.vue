<template>
  <div>
    <b-nav tabs>
      <b-nav-item disabled>
        <b>Fancy Questions App</b>
      </b-nav-item>
      <b-nav-item disabled>Counter: {{correctAnswers}}/{{total}}</b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: ["correctAnswers", "total"]
};
</script>