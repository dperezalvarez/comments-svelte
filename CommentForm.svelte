<script>

  

  </script>
  
  <form on:submit|preventDefault={handleSubmit}>
    <input
      bind:value={author}
      placeholder="Tu nombre"
    />
    <textarea
      bind:value={content}
      placeholder="Tu comentario"
    ></textarea>
    <button type="submit">Enviar</button>
  </form>
  