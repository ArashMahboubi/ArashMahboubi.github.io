# arashmahboubi.github.io
Arash Mahboubi Academic Portfolio 
fetch('https://example.com')
  .then(response => response.text())
  .then(html => {
    document.getElementById('content').innerHTML = html;
  })
  .catch(error => console.error('Error loading the page: ', error));
