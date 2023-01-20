<svg fill="none" viewBox="0 0 540 767" width="540" height="767" xmlns="http://www.w3.org/2000/svg">
    <foreignObject width="100%" height="100%">
        <div xmlns="http://www.w3.org/1999/xhtml">
            <style>
                * {
                    box-sizing: border-box;
                }

                body {
                    background: #dedede;
                    color: #FFFFFF;
                    font-family: 'Lato', sans-serif;
                }

                h2 {
                    margin: 0;
                    font-size: 2rem;
                    text-shadow: 0px 2px 2px rgb(0 0 0 / 25%), 0px 2px 4px rgb(0 0 0 / 25%);
                }

                h3 {
                    margin: 0;
                    color: #A79AE0;
                    font-style: normal;
                    font-weight: 400;
                    font-size: 1.5rem;
                }

                header {
                    text-align: center;
                }

                .card-container {
                    display: flex;
                    flex-direction: column;
                    align-items: center;
                    max-width: 540px;
                    margin: 0 auto;
                    gap: 1.5rem;

                    padding: 2rem 1rem;
                    border-radius: 2rem;

                    box-shadow: 0px 4px 75px rgba(0, 0, 0, 0.25);

                    background: #26235C;

                    border-bottom: 10px solid #F7DF1E;
                }

                .img-full-container {
                    padding: 0.5rem;
                    border-radius: 50%;
                    border: 2px solid transparent;
                    background: linear-gradient(45deg, #26235C, #26235C, #F7DF1E) border-box;
                }

                .card-container .img-container {
                    position: relative;
                    display: flex;
                    align-items: center;
                    justify-content: center;

                    width: 12rem;
                    height: 12rem;

                    background: #FFF;
                    border: 3px solid #F7DF1E;
                    border-radius: 50%;
                }

                .card-container .img-container>img {
                    width: 90%;
                    border-radius: 35%;
                    /* border-image: linear-gradient(90deg, #26235C, #26235C, #F7DF1E) 1;
                    border-image-outset: 2rem; */
                }

                .img-credits-link {
                    bottom: 18px;
                    font-size: 10px;
                    position: absolute;
                    opacity: 0.25;
                }

                main {
                    padding: 1rem;
                    display: flex;
                    flex-direction: column;
                    opacity: 0.75;
                    gap: 1.5rem;
                    align-items: center;
                }

                main span {
                    text-align: center;
                    font-style: normal;
                    font-weight: 400;
                    font-size: 1.25rem;
                }

                main span strong {
                    color: #F7DF1E;
                }

                main .tech-imgs {
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    gap: 1rem;
                }

                button {
                    background: #A79AE0;
                    color: #FFFFFF;
                    font-weight: bold;
                    font-size: 1rem;
                    border: none;
                    border-radius: 0.25rem;
                    padding: 1rem 2rem;
                    width: fit-content;
                }
            </style>

            <div class="card-container">
                <div class="img-full-container">
                    <div class="img-container">
                        <img src="./imgs/cat.jpg" alt="Profile Picture" />
                        <a class="img-credits-link"
                            href="https://www.freepik.com/free-vector/expression-emotion-concept-set-cat-character-diffetent-animal-emotions_18779007.htm#query=cat%20avatars&position=10&from_view=keyword">Image
                            by jcomp on Freepik
                        </a>
                    </div>
                </div>
                <header>
                    <h2>
                        Samuel Formigheri
                    </h2>
                    <h3>
                        Web Developer
                    </h3>
                </header>
                <main>
                    <span>
                        Hello there! 👋 <br />
                        I am a ✨ Full Stack Web Developer from Brazil ✨. <br />
                        I’m currently working with <strong>.Net</strong> and <strong>React</strong>. <br />
                    </span>
                    <div class="tech-imgs">
                        <img src="./imgs/react.png" alt="React" width="48px" />
                        <img src="./imgs/dotnet.png" alt=". Net" width="48px" />
                    </div>
                    <span> ⚡ For more information about me...</span>
                    <button class="email-button">
                        samuel.formigheri@hotmail.com
                    </button>
                </main>
                <a href="https://www.linkedin.com/in/samuel-formigheri-573047128/" target="_blank"
                    rel="noopener noreferrer">
                    <img src="./imgs/linkedin.png" alt="Linkedin Icon" />
                </a>
            </div>
        </div>
    </foreignObject>
</svg>