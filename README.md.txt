CON CSS LE APLICAMOS ESTILO A DOCUMENTO HTML
html {
  font-family: 'Montserrat', sans-serif;
}
body 
{
  margin: 0;
  background-color: #efefef;
}

header
{
  background-color: gray;
  color: white;
  padding: 1px 2px;
}

header h1 
{
  font-size: 3rem;
  text-align: center;
}

.container
{
  width: 400px;
  margin: 0 auto;
}
section article
{
  transition: box-shadow 0.3s ease;
  background-color: #fff;
  margin: 1rem 0;
  border-radius: 0.5rem;
  padding: 0.25rem 0;
  cursor: pointer;

}
section article h2, section article p
{
  margin: 1rem;
}

section article:hover
{
  box-shadow: 0 0.1rem 0.4rem rgba(0, 0, 0, 3);
}

footer 
{
  background-color: gray;
  padding: 1rem;
  color: white;
}

footer  p
{
  float: right;
  margin: 0;
}
footer section p 
{
  margin: 0;
}
footer a 
{
  transition: color 0.3s ease; 
  color: white;
  text-decoration: none;
}
footer a:hover
{
  color: cornflowerblue;
}