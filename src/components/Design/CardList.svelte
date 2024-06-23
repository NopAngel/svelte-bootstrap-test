<script>
  import Card from "./Card.svelte";

  let post = [
    {
      name: "Juan",
      age: 20,
      img: "https://raw.githubusercontent.com/Angel45003/angelnieto.github.io/0ba37decf37c74b668e73d1c21b2779bc52e0712/img/avatar.svg",
      description:
        "¡Te ayudo para tu página!, con más rendimiento y más funcionalidades",
      mail: "juanfierros@hotmail.com",
    },
    {
      name: "Rick",
      img: "https://raw.githubusercontent.com/Angel45003/angelnieto.github.io/0ba37decf37c74b668e73d1c21b2779bc52e0712/img/avatar.svg",
      age: 18,
      description:
        "¡Te ayudo para tu página!, con más rendimiento y más funcionalidades",
      mail: "rick@hotmail.com",
    },
    {
      name: "Roberto",
      img: "https://raw.githubusercontent.com/Angel45003/angelnieto.github.io/0ba37decf37c74b668e73d1c21b2779bc52e0712/img/avatar.svg",
      age: 30,
      description:
        "¡Te ayudo para tu Software App!, con más rendimiento y más funcionalidades para tú App",
      mail: "roberto@gmail.com",
    },
    {
      name: "Michael",
      img: "https://raw.githubusercontent.com/Angel45003/angelnieto.github.io/0ba37decf37c74b668e73d1c21b2779bc52e0712/img/avatar.svg",
      age: 18,
      description:
        "¡Te ayudo para tu página!, con más rendimiento y más funcionalidades",
      mail: "michael@hotmail.com",
    },
    {
      name: "John",
      img: "https://raw.githubusercontent.com/Angel45003/angelnieto.github.io/0ba37decf37c74b668e73d1c21b2779bc52e0712/img/avatar.svg",
      age: 19,
      description:
        "¡Te ayudo para tu página!, con más rendimiento y más funcionalidades",
      mail: "juanfierros@hotmail.com",
    },
  ];
</script>

<div class="container text-center">
  <main class="row row-cols-3">
    {#each post as posts}
      <Card
        age={posts.age}
        name={posts.name}
        image={posts.img}
        mail={posts.mail}
        description={posts.description}
      />
    {/each}
  </main>
</div>
