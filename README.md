<div style="
    display: flex; 
    justify-content: center; 
    align-items: center; 
    gap: 20px; 
    font-size: 14px; 
    flex-wrap: wrap; /* İçerik taşarsa satır kaydırır */
">
  <img src="./github.gif" alt="Profile GIF" class="responsive-img" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=serhat-yildiz&theme=radical" alt="GitHub Streak" class="responsive-img-large" />
  <img src="./github.gif" alt="Profile GIF" class="responsive-img" />
</div>

<style>
  .responsive-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    transition: all 0.3s ease;
  }

  .responsive-img-large {
    width: 400px;
    max-width: 90%;
    transition: all 0.3s ease;
  }

  /* Ekran küçüldükçe resimler küçülsün */
  @media (max-width: 768px) {
    .responsive-img {
      width: 100px;
      height: 100px;
    }

    .responsive-img-large {
      width: 250px;
    }
  }

  @media (max-width: 480px) {
    .responsive-img {
      width: 80px;
      height: 80px;
    }

    .responsive-img-large {
      width: 200px;
    }
  }
</style>
