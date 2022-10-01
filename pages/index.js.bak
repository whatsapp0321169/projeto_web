import Head from 'next/head';
import styles from '../styles/Home.module.css';

export default function Home() {
  return (
    <div>
        <title>W3.CSS Template</title>
        <meta charSet="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css" />
        <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Karma" />
        <style dangerouslySetInnerHTML={{__html: "\nbody,h1,h2,h3,h4,h5,h6 {font-family: \"Karma\", sans-serif}\n.w3-bar-block .w3-bar-item {padding:20px}\n" }} />
        {/* Sidebar (hidden by default) */}
        <nav className="w3-sidebar w3-bar-block w3-card w3-top w3-xlarge w3-animate-left" style={{display: 'none', zIndex: 2, width: '40%', minWidth: '300px'}} id="mySidebar">
          <a href="javascript:void(0)" onclick="w3_close()" className="w3-bar-item w3-button">Close Menu</a>
          <a href="#food" onclick="w3_close()" className="w3-bar-item w3-button">Comida</a>
          <a href="#about" onclick="w3_close()" className="w3-bar-item w3-button">Restaurant</a>
        </nav>
        {/* Top menu */}
        <div className="w3-top">
          <div className="w3-white w3-xlarge" style={{maxWidth: '1200px', margin: 'auto'}}>
            <div className="w3-button w3-padding-16 w3-left" onclick="w3_open()">☰</div>
            <img src="/logo1.png" style={{width: '10%'}} />
            <div className="w3-center w3-padding-16">Restaurant</div>
          </div>
        </div>
        {/* !PAGE CONTENT! */}
        <div className="w3-main w3-content w3-padding" style={{maxWidth: '1200px', marginTop: '100px'}}>
          {/* First Photo Grid*/}
          <div className="w3-row-padding w3-padding-16 w3-center" id="food">
            <div className="w3-quarter">
              <img src="/banana frita.png" alt="Batata frita" style={{width: '100%'}} />
              <h3>Banana Frita</h3>
            </div>
            <div className="w3-quarter">
              <img src="/lasanha.jpeg" alt="Lasanha" style={{width: '78%'}} />
              <h3>Lasanha a Bolonhesa</h3>
            </div>
            <div className="w3-quarter">
              <img src="/Macarrão.jpeg" alt="Macarrão" style={{width: '84%'}} />
              <h3>Macarrão</h3>
            </div>
            <div className="w3-quarter">
              <img src="/Pernil de cordeiro.jpeg" alt="Pernil" style={{width: '88%'}} />
              <h3>Pernil de cordeiro</h3>
            </div>
          </div>
          {/* Second Photo Grid*/}
          <div className="w3-row-padding w3-padding-16 w3-center">
            <div className="w3-quarter">
              <img src="/ratatoullie.jpeg" alt="Ratatoullie" style={{width: '90%'}} />
              <h3>Ratatoullie</h3>
            </div>
            <div className="w3-quarter">
              <img src="/ensopado de carne caseiro.jpeg" alt="Ensopado" style={{width: '105%'}} />
              <h3>Ensopado</h3>
            </div>
            <div className="w3-quarter">
              <img src="/crepe.jpeg" alt="Crepe" style={{width: '87%'}} />
              <h3>Crepe</h3>
            </div>
            <div className="w3-quarter">
              <img src="/petti.jpg" alt="Petti Gateou" style={{width: '105%'}} />
              <h3>Petti Gateou </h3>
            </div>
          </div>
          {/* Pagination */}
          <div className="w3-center w3-padding-32">
            <div className="w3-bar">
              <a href="#" className="w3-bar-item w3-button w3-hover-black">«</a>
              <a href="#" className="w3-bar-item w3-black w3-button">1</a>
              <a href="#" className="w3-bar-item w3-button w3-hover-black">2</a>
              <a href="#" className="w3-bar-item w3-button w3-hover-black">3</a>
              <a href="#" className="w3-bar-item w3-button w3-hover-black">4</a>
              <a href="#" className="w3-bar-item w3-button w3-hover-black">»</a>
            </div>
          </div>
          <hr id="about" />
          {/* About Section */}
          <div className="w3-container w3-padding-32 w3-center">  
            <h3>Meu restaurante</h3><br />
            <img src="/RESTAURANTE.jpg" alt="Me" className="w3-image" style={{display: 'block', margin: 'auto'}} width={800} height={533} />
            <div className="w3-padding-32">
              <h4><b>Venha nos conhecer!</b></h4>
              <h6><i>As melhores lembranças são feitas de: Boa comida, bons amigos e bons momentos!
                  <p>Nosso restaurante é aconchegante e promete atender todos os pedidos do cliente fazendo com que ele se sinta acolhido e satisfeito com a nossa comida, prezamos a sua felicidade e o paladar principalmente!.
                    Aguardamos você aqui, obrigada pela atenção.
                  </p>
                </i></h6></div><i>
            </i></div><i>
            <hr />
            {/* Footer */}
            <footer className="w3-row-padding w3-padding-32">
              <div className="w3-third">
                <h3>BLOG POSTS</h3>
                <ul className="w3-ul w3-hoverable">
                  <li className="w3-padding-16">
                    <img src="/LOGO INSTA.png" className="w3-left w3-margin-right" style={{width: '50px'}} />
                    <span className="w3-large">@Restaurant_food</span><br />
                    <span>Nos siga para ficar dentro de todas as novidades!</span>
                  </li>
                </ul>
              </div>
              <div className="w3-third w3-serif">
                <h3>POPULAR TAGS</h3>
                <p>
                  <span className="w3-tag w3-black w3-margin-bottom">Travel</span> <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">New York</span> <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">Dinner</span>
                  <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">Salmon</span> <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">France</span> <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">Drinks</span>
                  <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">Ideas</span> <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">Flavors</span> <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">Cuisine</span>
                  <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">Chicken</span> <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">Dressing</span> <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">Fried</span>
                  <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">Fish</span> <span className="w3-tag w3-dark-grey w3-small w3-margin-bottom">Duck</span>
                </p>
              </div>
            </footer>
            {/* End page content */}
          </i></div><i>
        </i></div>
  );
}
