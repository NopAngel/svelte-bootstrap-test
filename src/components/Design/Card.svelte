<script>
  export let name;
  export let age;
  export let image;
  export let mail;

  export let description;
</script>

<article class="card gap-4 col" style="width: 18em;margin:10px;">
  <img width="100%" height="100%" src={image} alt={name} />
  <div class="card-body">
    <h1 class="card-title">{name}</h1>
    <h2 class="btn btn-link">{mail}</h2>
    <p
      class="card-text"
      style="width: 100%;text-align: left;font-size: 15px;opacity:80%;"
    >
      {description}
    </p>
    <button class="btn btn-primary">Contratar.</button>
  </div>
</article>
