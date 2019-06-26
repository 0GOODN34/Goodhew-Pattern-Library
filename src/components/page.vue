<template>
  <div>
    <nav>
      <div class="title">
        <p>Goodhew Library</p>
      </div>
      <ul class="links">
        <li><a href="#grid-link">Grid</a></li>
        <li><a href="#nav-link">Navigation</a></li>
        <li><a href="#header-link">Header</a></li>
        <li><a href="#button-link">Button</a></li>
        <li><a href="#jumbo-link">Jumbotron</a></li>
        <li><a href="#footer-link">Footer</a></li>
      </ul>
    </nav>
    <div class="container">
      <div class="column-row">
        <div class="column intro">
          <h1>The Goodhew Library</h1>
          <p>The pattern library for people that want to be simple; black, white and grey</p>
          <a href="https://github.com/0GOODN34/Goodhew-Pattern-Library" class='button white' target="_blank">Download the Pattern Library Here on github</a>
          <p>
            To use the goodhew library, simply use the follow code line in your head tag:
            <code>
              <pre>
                &lt;link href=&quot;goodhew-library.css&quot; rel=&quot;stylesheet&quot;/&gt;
              </pre>
            </code>
          </p>
        </div>
      </div>
    </div>
      <div class="container" id="grid-link">
        <h2>Columns Grid System</h2>
        <section class="column-row">
          <div class="column">1</div>
        </section>
        <div class="column-row">
          <div class="column">1</div>
          <div class="column">2</div>
        </div>
        <div class="column-row">
          <div class="column">1</div>
          <div class="column">2</div>
          <div class="column">3</div>
        </div>
        <div class="column-row">
          <div class="column">1</div>
          <div class="column">2</div>
          <div class="column">3</div>
          <div class="column">4</div>
        </div>
        <div class="column-row">
          <div class="column">1</div>
          <div class="column">2</div>
          <div class="column">3</div>
          <div class="column">4</div>
          <div class="column">5</div>
        </div>
        <div class="column-row">
          <div class="column">1</div>
          <div class="column">2</div>
          <div class="column">3</div>
          <div class="column">4</div>
          <div class="column">5</div>
          <div class="column">6</div>
        </div>
        <div class="column-row">
          <div class="column">1</div>
          <div class="column">2</div>
          <div class="column">3</div>
          <div class="column">4</div>
          <div class="column">5</div>
          <div class="column">6</div>
          <div class="column">7</div>
        </div>
        <div class="column-row">
          <div class="column">1</div>
          <div class="column">2</div>
          <div class="column">3</div>
          <div class="column">4</div>
          <div class="column">5</div>
          <div class="column">6</div>
          <div class="column">7</div>
          <div class="column">8</div>
        </div>
        <div class="column-row">
          <div class="column">1</div>
          <div class="column">2</div>
          <div class="column">3</div>
          <div class="column">4</div>
          <div class="column">5</div>
          <div class="column">6</div>
          <div class="column">7</div>
          <div class="column">8</div>
          <div class="column">9</div>
        </div>
        <div class="column-row">
          <div class="column">1</div>
          <div class="column">2</div>
          <div class="column">4</div>
          <div class="column">5</div>
          <div class="column">6</div>
          <div class="column">7</div>
          <div class="column">8</div>
          <div class="column">9</div>
          <div class="column">10</div>
        </div>
        <div class="column-row">
          <div class="column">1</div>
          <div class="column">2</div>
          <div class="column">3</div>
          <div class="column">4</div>
          <div class="column">5</div>
          <div class="column">6</div>
          <div class="column">7</div>
          <div class="column">8</div>
          <div class="column">9</div>
          <div class="column">10</div>
          <div class="column">11</div>
        </div>
        <div class="column-row">
          <div class="column">1</div>
          <div class="column">2</div>
          <div class="column">3</div>
          <div class="column">4</div>
          <div class="column">5</div>
          <div class="column">6</div>
          <div class="column">7</div>
          <div class="column">8</div>
          <div class="column">9</div>
          <div class="column">10</div>
          <div class="column">11</div>
          <div class="column">12</div>
        </div>
        
        <div class="column-row">
          <div class="column">
            <h3>Code</h3>
            <code>
              <pre>
              &lt;div class=&quot;column-row&quot;&gt;
                &lt;div class=&quot;column&quot;&gt;However many columns you want&lt;/div&gt;
              &lt;/div&gt;
              </pre>
              </code>
          </div>
        </div>
      </div>
      <div class="container" id="nav-link">
        <h2>Nav Bar</h2>
        <div class="column-row">
          <div class="column">
            <nav class='not-fixed'>
              <div class="title">
                <p>Title</p> 
              </div>
              <ul class="links">
                <li><a href="#">Link</a></li>
                <li><a href="#">Link 2</a></li>
                <li><a href="#">Link 3</a></li>
                <li><a href="#">Link 4</a></li>
                <li><a href="#">Link 5</a></li>
              </ul>
            </nav>
          </div>
         
        </div>
            <div class="column-row">
              <div class="column">
                <h3>
                  Code
                </h3>
                <code>
                  <pre>
            &lt;nav class='not-fixed'&gt;
              &lt;div class=&quot;title&quot;&gt;
                &lt;p&gt;Title&lt;/p&gt; 
              &lt;/div&gt;
              &lt;ul class=&quot;links&quot;&gt;
                &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Link&lt;/a&gt;&lt;/li&gt;
                &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Link 2&lt;/a&gt;&lt;/li&gt;
                &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Link 3&lt;/a&gt;&lt;/li&gt;
                &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Link 4&lt;/a&gt;&lt;/li&gt;
                &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Link 5&lt;/a&gt;&lt;/li&gt;
              &lt;/ul&gt;
            &lt;/nav&gt;
                  </pre>
                </code>
              </div>
          </div>
      </div>
      <div class="container" id="header-link">
        <div class="column-row">
          <div class="column">
            <h2>Header Carousel</h2>
            <header class="header">
              <div class="slides">
                <div class="slide one">
                  <h2>Slide Title</h2>
                  <p>Slide Description</p>
                  <a href="" class="button">Slide Button</a>
                </div>
                
                <div class="slide two">
                  <img src="https://images.unsplash.com/photo-1493540447904-49763eecf55f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80" alt="">
                  <h2>Slide with image</h2>
                  <p>Slide Description</p>
                  <a href="" class="button">Slide Button</a>
                </div>
                   <div class="slide three">
                  <h2>Slide Title</h2>
                  <p>Slide Description</p>
                  <a href="" class="button">Slide Button</a>
                </div>
                
                <div class="slide four">
                  <img src="https://images.unsplash.com/photo-1493540447904-49763eecf55f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80" alt="">
                  <h2>Slide with image</h2>
                  <p>Slide Description</p>
                  <a href="" class="button">Slide Button</a>
                </div>
                   <div class="slide five">
                  <h2>Slide Title</h2>
                  <p>Slide Description</p>
                  <a href="" class="button">Slide Button</a>
                </div>
                
                <div class="slide six">
                  <img src="https://images.unsplash.com/photo-1493540447904-49763eecf55f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80" alt="">
                  <h2>Slide with image</h2>
                  <p>Slide Description</p>
                  <a href="" class="button">Slide Button</a>
                </div>
              </div>
            </header>
          </div>
        </div>
        <div class="column-row">
          <div class="column">
            <h3>Code</h3>
            <p>Important to note: You can add a background, just add the image first. This slideshow only allows 6 slides</p>
            <code>
              <pre>
           &lt;header class=&quot;header&quot;&gt;
              &lt;div class=&quot;slides&quot;&gt;
                &lt;div class=&quot;slide one&quot;&gt;
                  &lt;h2&gt;Slide Title&lt;/h2&gt;
                  &lt;p&gt;Slide Description&lt;/p&gt;
                  &lt;a href=&quot;&quot; class=&quot;button&quot;&gt;Slide Button&lt;/a&gt;
                &lt;/div&gt;
                
                &lt;div class=&quot;slide two&quot;&gt;
                  &lt;img src=&quot;https://images.unsplash.com/photo-1493540447904-49763eecf55f?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=1350&amp;q=80&quot; alt=&quot;&quot;&gt;
                  &lt;h2&gt;Slide with image&lt;/h2&gt;
                  &lt;p&gt;Slide Description&lt;/p&gt;
                  &lt;a href=&quot;&quot; class=&quot;button&quot;&gt;Slide Button&lt;/a&gt;
                &lt;/div&gt;
                   &lt;div class=&quot;slide three&quot;&gt;
                  &lt;h2&gt;Slide Title&lt;/h2&gt;
                  &lt;p&gt;Slide Description&lt;/p&gt;
                  &lt;a href=&quot;&quot; class=&quot;button&quot;&gt;Slide Button&lt;/a&gt;
                &lt;/div&gt;
                
                &lt;div class=&quot;slide four&quot;&gt;
                  &lt;img src=&quot;https://images.unsplash.com/photo-1493540447904-49763eecf55f?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=1350&amp;q=80&quot; alt=&quot;&quot;&gt;
                  &lt;h2&gt;Slide with image&lt;/h2&gt;
                  &lt;p&gt;Slide Description&lt;/p&gt;
                  &lt;a href=&quot;&quot; class=&quot;button&quot;&gt;Slide Button&lt;/a&gt;
                &lt;/div&gt;
                   &lt;div class=&quot;slide five&quot;&gt;
                  &lt;h2&gt;Slide Title&lt;/h2&gt;
                  &lt;p&gt;Slide Description&lt;/p&gt;
                  &lt;a href=&quot;&quot; class=&quot;button&quot;&gt;Slide Button&lt;/a&gt;
                &lt;/div&gt;
                
                &lt;div class=&quot;slide six&quot;&gt;
                  &lt;img src=&quot;https://images.unsplash.com/photo-1493540447904-49763eecf55f?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=1350&amp;q=80&quot; alt=&quot;&quot;&gt;
                  &lt;h2&gt;Slide with image&lt;/h2&gt;
                  &lt;p&gt;Slide Description&lt;/p&gt;
                  &lt;a href=&quot;&quot; class=&quot;button&quot;&gt;Slide Button&lt;/a&gt;
                &lt;/div&gt;
              &lt;/div&gt;
            &lt;/header&gt;
              </pre>
            </code>
          </div>
        </div>
      </div>
      <div class="container" id="button-link">
        <div class="column-row">
          <div class="column">
            <h2>Buttons</h2>
           
          </div>
        </div>
        <div class="column-row">
          <div class="column">
            <button class='button'>Button</button>
          </div>
          <div class="column">
            <h3>Standard Button</h3>
             <code>
              <pre>
                &lt;button class='button'&gt;Button&lt;/button&gt;
              </pre>
            </code>
          </div>
        </div>
         <div class="column-row">
          <div class="column">
            <button class='button large'>Large Button</button>
          </div>
          <div class="column">
            <h3>Large Button</h3>
            
             <code>
              <pre>
                &lt;button class='button large'&gt;Button&lt;/button&gt;
              </pre>
            </code>
          </div>
        </div>
         <div class="column-row">
          <div class="column">
            <button class='button small'>Small Button</button>
          </div>
          <div class="column">
            <h3>Small Button</h3>
            
             <code>
              <pre>
                &lt;button class='button small'&gt;Button&lt;/button&gt;
              </pre>
            </code>
          </div>
        </div>
         <div class="column-row">
          <div class="column">
            <button class='button white'>White Button</button>
          </div>
          <div class="column">
            <h3>White Button</h3>
            
             <code>
              <pre>
                &lt;button class='button white'&gt;Button&lt;/button&gt;
              </pre>
            </code>
          </div>
        </div>
         <div class="column-row">
          <div class="column">
            <button class='button grey'>Grey Button</button>
          </div>
          <div class="column">
            <h3>Grey Button</h3>
            
             <code>
              <pre>
                &lt;button class='button grey'&gt;Button&lt;/button&gt;
              </pre>
            </code>
          </div>
        </div>
         <div class="column-row">
          <div class="column">
            <button class='button text'>Text Button</button>
          </div>
          <div class="column">
            <h3>Text Button</h3>
            
             <code>
              <pre>
                &lt;button class='button text'&gt;Button&lt;/button&gt;
              </pre>
            </code>
          </div>
        </div>
      </div>
      <div class="container" id="jumbo-link">
        <div class="column-row">
          <div class="column">
            <h2>Jumbotron</h2>
            <section class="jumbo">
              <h2 class="title">
                The great marketing title!
              </h2>
              <p>A simple message to go with our efforts of selling you this!</p>
              <a href="" class='button'>Read More!</a>
            </section>
          </div>
        </div>
        <div class="column-row">
          <div class="column">
            <h3>Code</h3>
            <code>
              <pre>
           &lt;section class=&quot;jumbo&quot;&gt;
              &lt;h2 class=&quot;title&quot;&gt;
                The great marketing title!
              &lt;/h2&gt;
              &lt;p&gt;A simple message to go with our efforts of selling you this!&lt;/p&gt;
              &lt;a href=&quot;&quot; class='button'&gt;Read More!&lt;/a&gt;
            &lt;/section&gt;
              </pre>
            </code>
          </div>
        </div>
      </div>
      <div class="container" id="footer-link">
        <div class="column-row">
          <div class="column">
            <h2>Footer</h2>
            <footer>
              <div class="container">
                <div class="footer-site-title">
                  <h3>The Great Title</h3>
                  <p>A great quote to go with the title</p>
                </div>
                <div class="footer-extra-detail">
                  <div class="social">
                    <a href="">
                      <img src="https://cdn4.iconfinder.com/data/icons/social-media-icons-the-circle-set/48/facebook_circle-512.png" alt="">
                    </a>
                    <a href="">
                      <img src="https://cdn3.iconfinder.com/data/icons/social-icons-5/606/Twitter.png" alt="">
                    </a>
                  </div>
                  <div class="extra-links">
                    <a href="">Sitemap</a>
                    <a href="">Privacy Policy</a>
                    <a href="">Contact</a>
                  </div>
                  <div class="copyright">
                    &copy; Copyright of 2019
                  </div>
                </div>
              </div>
            </footer>
          </div>
        </div>
        <div class="column-row">
          <div class="column">
            <h3>Code</h3>
            <code>
              <pre>
           &lt;footer&gt;
              &lt;div class=&quot;container&quot;&gt;
                &lt;div class=&quot;footer-site-title&quot;&gt;
                  &lt;h3&gt;The Great Title&lt;/h3&gt;
                  &lt;p&gt;A great quote to go with the title&lt;/p&gt;
                &lt;/div&gt;
                &lt;div class=&quot;footer-extra-detail&quot;&gt;
                  &lt;div class=&quot;social&quot;&gt;
                    &lt;a href=&quot;&quot;&gt;
                      &lt;img src=&quot;https://cdn4.iconfinder.com/data/icons/social-media-icons-the-circle-set/48/facebook_circle-512.png&quot; alt=&quot;&quot;&gt;
                    &lt;/a&gt;
                    &lt;a href=&quot;&quot;&gt;
                      &lt;img src=&quot;https://www.pngkey.com/png/detail/2-27646_twitter-logo-png-transparent-background-logo-twitter-png.png&quot; alt=&quot;&quot;&gt;
                    &lt;/a&gt;
                  &lt;/div&gt;
                  &lt;div class=&quot;extra-links&quot;&gt;
                    &lt;a href=&quot;&quot;&gt;Sitemap&lt;/a&gt;
                    &lt;a href=&quot;&quot;&gt;Privacy Policy&lt;/a&gt;
                    &lt;a href=&quot;&quot;&gt;Contact&lt;/a&gt;
                  &lt;/div&gt;
                  &lt;div class=&quot;copyright&quot;&gt;
                    © Copyright of 2019
                  &lt;/div&gt;
                &lt;/div&gt;
              &lt;/div&gt;
            &lt;/footer&gt;
              </pre>
            </code>
          </div>
        </div>
      </div>
      <div class="container">
        <div class="column-row">
          <div class="column">
            <h2>Modal</h2>
            <div class="modal appear not-fixed" id="example-modal-1">
              <div class="modal-inside">
              <div class="modal-title">
                Modal Title
              </div>
              <div class="modal-content">
                <p>This is the modal content to go with the model so that there is something there that people can read</p>
              </div>
              <div class="model-buttons">
                <button class="button" v-on:click="closeModal('example-modal-1')">Close</button>
              </div>
              </div>
            </div>

            
          </div>
        </div>
        <div class="column-row">
          <div class="column">
            <button class="button" v-on:click="openModal('example-modal-2')">Open Modal</button>
            <div class="modal" id="example-modal-2">
              <div class="modal-inside">
              <div class="modal-title">
                Modal Title
              </div>
              <div class="modal-content">
                <p>This is the modal content to go with the model so that there is something there that people can read</p>
              </div>
              <div class="model-buttons">
                <button class="button" v-on:click="closeModal('example-modal-2')">Close</button>
              </div>
              </div>
            </div>
          </div>
        </div>
        <div class="column-row">
          <div class="column">
            <h3>Code</h3>
            <p>
              A click event is required on any element (This example is a button) which will add a classname 'appear' to the modal.
            </p>
            <p>A close button in the modal will require a click event that will remove the clasname appear from the modal</p>
            <p>Current example based on Vue.js</p>
            <code>
              <pre>
         &lt;button class=&quot;button&quot; v-on:click=&quot;openModal('example-modal-2')&quot;&gt;Open Modal&lt;/button&gt;
            &lt;div class=&quot;modal&quot; id=&quot;example-modal-2&quot;&gt;
              &lt;div class=&quot;modal-inside&quot;&gt;
              &lt;div class=&quot;modal-title&quot;&gt;
                Modal Title 
              &lt;/div&gt;
              &lt;div class=&quot;modal-content&quot;&gt;
                &lt;p&gt;This is the modal content to go with the model so that there is something there that people can read&lt;/p&gt;
              &lt;/div&gt;
              &lt;div class=&quot;model-buttons&quot;&gt;
                &lt;button class=&quot;button&quot; v-on:click=&quot;closeModal('example-modal-2')&quot;&gt;Close&lt;/button&gt;
              &lt;/div&gt;
              &lt;/div&gt;
            &lt;/div&gt;
              </pre>
            </code>
          </div>
        </div>
      </div>
       <footer>
              <div class="container">
                <div class="footer-site-title">
                  <h3>Goodhew Library</h3>
                  <p>Going back to basics; black, white and grey</p>
                </div>
                <div class="footer-extra-detail">
                  <div class="social">
                    <a href="">
                      <img src="https://cdn4.iconfinder.com/data/icons/social-media-icons-the-circle-set/48/facebook_circle-512.png" alt="">
                    </a>
                    <a href="">
                      <img src="https://cdn3.iconfinder.com/data/icons/social-icons-5/606/Twitter.png" alt="">
                    </a>
                  </div>
                  <div class="extra-links">
                    <a href="">Sitemap</a>
                    <a href="">Privacy Policy</a>
                    <a href="">Contact</a>
                  </div>
                  <div class="copyright">
                    &copy; Copyright of 2019
                  </div>
                </div>
              </div>
            </footer>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  methods: {
    openModal(id) {
      var modal = document.getElementById(id)
      modal.className += " appear"
    },
    closeModal(id) {
      var modal = document.getElementById(id)
      modal.classList.remove('appear')
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >
@import "../assets/goodhew-library.css";

.intro *{
  text-align: center;

}
</style>
 