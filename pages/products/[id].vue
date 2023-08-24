<template>
  <div>
    <p>Products details for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia
      obcaecati laborum ut ipsam odio voluptatum voluptatem? Itaque quos
      provident nostrum incidunt error ratione est, sunt quis ullam? Ea, sunt
      doloremque.
    </p>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illo repellat
      veritatis cupiditate dolor fuga reprehenderit aliquam optio dolorum animi
      dolorem iure nostrum unde, provident eveniet voluptatibus distinctio!
      Nihil, modi dicta?
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;
</script>

<style scoped></style>
