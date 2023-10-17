<script lang="ts">
  const currentTime = new Date();
  const currentHour = currentTime.getHours();

  let greeting = "";

  if (currentHour >= 5 && currentHour < 12) {
    greeting = "Hey there, Good morning";
  } else if (currentHour >= 12 && currentHour < 18) {
    greeting = "Good afternoon bud";
  } else {
    greeting = "Good night, should I play some Lofi music?";
  }
</script>

<h1 class="text-3xl font-bold">{greeting}</h1>
