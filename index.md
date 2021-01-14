<html>
<head>
         <title>User Page</title>
         <link rel="stylesheet" href="admin.css" title="" type="text/css" media="screen" charset="utf-8">
</head>
         
<body>
<nav class="menu">
  <ol>
    <li><a href="#">Han Dyasty</a></li>
    <li><a href="#">Chelsea FC</a></li>
    <li><a href="#">Contact</a></li>
  </ol>
</nav>

<main id="main-content">
   <h1>Welcome to Zhichao Liu's GitHub Page</h1>
   <p> You can find the <span>course website</span> in <a href="https://canvas.ucsd.edu/courses/21783">UCSD 110 Canvas</a> </p>
   <p> You can edit this file by changing the <a href="./_config.yml">configure file</a> </p>
  
<article class="Introduction">
    <header>
      <h2>Introduction to myself</h2>
    </header>
    <section class = "personal statement">
         <p> My name is Zhichao Liu, a international student from China. And in this user page, I will introduce some interests I have.</p>
         <p> First of all, my favirate language is Java </p>
         <code> System.out.println ("I love Java!"); </code>  
         <p></p>
         <label for="Languae-select">Choose the language you like the most:</label>   
         <select id="Language-select">
               <option value="">--Please choose an option--</option>
               <option value="Java">Java</option>
               <option value="C++/C">C/C++</option>
               <option value="Python">Python</option>
               <option value="Js">Java Script</option>
               <option value="Go">Go</option>
               <option value="Others">Others</option>
        </select>
    </section>
    <section class = "interests">
         <p> Then, I will list my interests as ordered list: </p>
             <ol>
                  <li> Chinese Ancient History  </li>
                  <li> Soccer  </li>
                  <li> Drawing </li>
                  <li> Writing  </li>
                  <li> Japanese Animation </li>
             </ol>
    </section>
         
<article>
   
<hr>
<article class="Han Dyasty">
    <header>
      <h2>Information of Western Han Dyasty</h2>
    </header>
    <section class = "main_overview">
             <p> the Han dynasty (Chinese: <code>漢朝</code>; pinyin: Hàncháo) was the second imperial dynasty of China <em class="time">(202 BC – 220 AD)</em>, established by the rebel leader <strong class="name">Liu Bang</strong> and ruled by the <b class="name">House of Liu</b>. Preceded by the short-lived Qin dynasty <em class="time">(221–206 BC)</em> and a warring interregnum known as the Chu–Han contention <em class="time">(206–202 BC)</em>, it was briefly interrupted by the Xin dynasty <em class="time">(9–23 AD)</em> established by the usurping regent <strong class="name">Wang Mang</strong>, and was separated into two periods—the Western Han <em class="time">(202 BC–9 AD)</em> and the Eastern Han <em class="time">(25–220 AD)</em>, before being succeeded by the Three Kingdoms period <em class="time">(220–280 AD)</em>. </p>
    </section>
    <aside>
        <p> <strong> Han Dyasty is one of the flourishing and powerful period in Chinese Ancient History </strong> </p>
    </aside>
    <div class="Pic for Han">
    <img width="600" height="400" src="https://images.chinahighlights.com/allpicture/2017/04/easternhan.jpg"
         alt="Han pic">
    <p>The map for Han Dyasty</p>
    </div>
    <hr>
    <section class="people">
        <h3>Founder</h3>
        <p>Bang Liu (Han Gao Zu)</p>
        <figure>
            <img width="230" height="300" src="https://www.holoong.com/uploadculture/big/052104153120143615.jpg"
                 alt="Liu Bang's pic">
             <figcaption><em>Liu Bang</em></figcaption>
        </figure>
        <h3>Famous Emperors</h3>
            <ol>Che Liu (Han Wu) </ol> 
            <ol>Xun Liu(Han Xuan) </ol>
        <h3>Great Generals</h3>
            <ul>Xin Han</ul> 
            <ul>Qing Wei</ul>
            <ul>Qubing Huo</ul>
    </section>   
   <p> <a href="https://en.wikipedia.org/wiki/Han_dynasty">The reference</a> </p>
</article>
 
 
<hr>

<article class="Chelsea FC">
       <header>
            <h2>Introduction to Chelsea FC </h2>
       </header>
         <p> <strong>Chelsea Football Club </strong> are an English professional football club based in Fulham, London. Founded in <em>1905</em>, the club competes in the Premier League, the top division of English football. Chelsea are among England's most successful clubs, having won over <strong>thirty competitive honours</strong>, including <strong>six league titles</strong> and <strong>six European trophies</strong>. Their home ground is Stamford Bridge </p>       
       <div class = "pic for Chelsea">
           <img width="400" height="400" src="https://upload.wikimedia.org/wikipedia/en/thumb/c/cc/Chelsea_FC.svg/360px-Chelsea_FC.svg.png">
           <p>The symbol of Chelsea</p>
       </div>   
       <iframe width="600" height="400" src="https://www.youtube.com/embed/BYdnj9delqw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
       <label for="Choose Champion">Choose the Team you think is Champion in Premier League: </label>
           <select id="Choose Champion">
                <optgroup>
                   <option>Chelsea</option>
                   <option>Manchester City</option>
                   <option>Manchester United</option>
                   <option>Spurs</option>
                   <option>Arsenal</option>
                   <option>Liverpool</option>
                   <option>Leichester City</option>
                   <option>Others</option>
               </optgroup>
          </select>
      <form>
          <fieldset>
               <legend>Choose the ranking Chelsea will be: </legend>
                  <input type="radio" id="1" name="rank">
                        <label for="1">1st (Champion!)</label><br/>
                  <input type="radio" id="2" name="rank">
                       <label for="2">2nd</label><br/>
                 <input type="radio" id="3" name="rank">
                       <label for="3">3rd</label><br/>
                 <input type="radio" id="4" name="rank">
                       <label for="4">4th</label><br/>
                 <input type="radio" id=">4" name="rank">
                       <label for=">4">>4 (Oh No!)</label><br/>
         </fieldset>
     </form>  
     <label for="Truth">Tell you the truth:</label><br>
        <textarea id="truth" name="truth"
            rows="5" cols="33">
            Chelsea plays like shit this season, and I don't really expect it can enter top 4... :(
        </textarea>
</article>



<article class="Animation">
         <header>
                  <h2>Japanese Animation</h2>
         </header>
        <p> My favirate Animations are <a href="https://en.wikipedia.org/wiki/Attack_on_Titan">Attack on Titan</a> and <a href="https://en.wikipedia.org/wiki/Fullmetal_Alchemist">Fullmetal Alchemist</a> </p>
         <picture>
             <source srcset="https://hb.imgix.net/efc2778399ad3916e3d0ecdd52d2baf506fe41ae.jpg?auto=compress,format&fit=crop&h=353&w=616&s=725ab9c50a405a056f72d00e76ac04d4" media="(min-width: 600px)">
             <img width="600" height="400" src="https://cdn1.i-scmp.com/sites/default/files/2015/06/15/maxresdefault.jpg" alt="" />
        </picture>
        <figure>
            <figcaption>Here is my favirate music in the animation:</figcaption>
            <audio
               controls
                 src="./YouSeeBIGGIRL.mp3">
                 Your browser does not support the <code>audio</code> element.
            </audio>
       </figure>
        <canvas width="300" height="100">
                Canvas for White.
        </canvas>
        <p> That is the BGM from Attack on Titan! </p>
         <p> Now the question is: Do you like <strong> Animation </strong>? <br>
             If the answer is <strong> YES </strong>, tell me your favirate animation! </p>
        <form action="" method="get" class="enter_animation">
               <div class="enter_animation">
                   <label for="Yes/No">Yes or No: </label>
                   <input type="text" name="YN" id="YN" required>
               </div>
               <div class="enter_animation">
                    <label for="Animation">If yes, enter your favirate animation: </label>
                    <input type="text" name="name" id="name" required>
               </div>
               <div class="enter_animation">
                    <input type="submit" value="Subscribe!">
               </div>
       </form>
  
       

</article>


<hr>

<article class="contact">
     <header>
        <h2>Contact to me</h2>
    </header>
    <p> If you have any interest in my project, feel free to send me message through email: <strong> z5liu@ucsd.edu </strong> </p>
    <p> In the future, I will use <em>CSS</em> and <em>JavaScript</em> to make the page more beautiful and active! </p>
    <p> For example, I may use the following code to change color/size/style of text! </p>
    <pre> 
      body1 {                         body2 {                                  body3 {
          color: red;                    font-size: .7rem;                         margin: 0;
      }                               }                                        }
    </pre>                           
</article>

<hr>

<h3> Address: </h3>
<p> 
    19 Lambert Drive, <br>
    Princeton, NJ <br>
    08540 <br>
    U.S <br>
</p>
<table>
         <thead> <tr>
             <th colspan="2">Date</th>
         </tr> </thead>
      <tbody> <tr>
            <td>Jan 14</td>
            <td>2021</td>
      </tr> </tbody>
   </table>

</main>
</body>
</html>

