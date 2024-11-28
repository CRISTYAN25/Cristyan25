import {movies} from ‘./movies.js’;

document.getElementByld(‘filmform’).addEventListener(‘submit’, function (event) {

  event.preventDefault(); // Evita o envio do formulário

// Obtém a idade e categorias selecionadas 

let age = parselnt(document.getElementByld(‘age’). value); // Converte a idade para números 

let categories = document.querySelectorAll(‘input[name=”catrgory”]:checed’);

let selectedCategories = [];

for (let i = 0; i < categories.length; i ++) {

  selectedCategorias.push(categories[i]. Value);

}

// Filtra os filmes com base na idade e categorias let fileredMovies;

if (age >= 1 && age <= 9) {

  // Filtra filmes adequados para a idade de 0 a 9 filteredMovies = movies.filter(

  (movies) =>

   SelectedCategories.includes(movies.genre) && movies.ageRating <= age

  );

}

// Limpa os resultados anteriores 

Let moviesResults.innerHTML = “;


// Exibe os filmes 

for (let i = 0; i < filteredMovies.length; i++) {

  let movie = filteredMovies[i];

  let movieDiv = document.createElement(‘div’);

  movieDiv.classList.add(‘movie’);

  movieDiv.innerHTML = ‘

      <h3>${movie.title}</h3>

      <p>strong>gênero:</strong> ${movie.genre}</p>

      <p><strong>Sinopse:</strong> $(movies.sinopse)</p>

      <iframe widith = “550”height=”315”src=”$(movie.trailer)”

        frameborder=”0” allow=”accelerometer: autoplay, clipboard-media gyrospicturepicture-in-picture” allowfullscreen ></iframe>


  movieResults.appendChild(movieDiv) 

}

 // Se não houver filmes compatives 

 if (filteredMovies length === 0) {

    movieresults.innerHTML = <p>Nenhum filme encontrado para as categorias selecionadas.</p>’.

  }

}):


