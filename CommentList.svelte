<script>

  </script>
  
  <div>
    <h2>Comentarios</h2>
    <ul>
      {#each comments as {author, content}, index}
        <li key={index}>
          <strong>{author}</strong>: {content}
        </li>
      {/each}
    </ul>
  </div>
  