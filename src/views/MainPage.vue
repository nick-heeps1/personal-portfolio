<template>
    <div class="main-container">
        <div class="container-one">
            <div class="profile">
                <img src="../assets/profile-pic.png" alt="">
                <h1>Nicholas Heeps</h1>
                <h2> IT student</h2>
            </div>
            <div class="social-links">
                    <div class ="link">
                      <a href="https://github.com/nick-heeps1">
                        <img src="../assets/github.png" alt="">
                        <h2>GitHub</h2>
                      </a>
                    </div>
                    <div class ="link">
                      <a href="https://www.linkedin.com/in/nicholas-heeps-189983236/">
                        <img src="../assets/LinkedIn.png" alt="">
                        <h2>LinkedIn</h2>
                      </a>
                    </div>
                    <div class ="link">
                      <a href="https://www.youtube.com/channel/UCfIYBNfilN8YQbqf8BroyiQ">
                        <img src="../assets/youtube.png" alt="">
                        <h2>YouTube</h2>
                      </a>
                    </div>
            </div>
        </div>
        <div class="container-two">
            <div class="Description">
                <h1>About Me</h1>
                <p>Hey my name is Nick, my Deakin student number is s223167228 and my email address is s223167228@deakin.edu.au. I am a new student here at Deakin and I’m currently studying for a bachelor’s degree in information technology. 
                    I live at Deakin residence and have 3 days a week of contact. This is my second year at university as I had originally started off at RMIT but had decided to transfer as Deakin was more appealing to me. 
                    Before moving to Melbourne, I used to live on a farm in a small town near the border called Barnawartha. 
                </p>
                <p>
                    I have a few different hobbies, but my main ones are coding, building PC’s and going to gym. Since first beginning university, I have created a few projects including writing a choose your own adventure game in python, 
                    creating a basic bartending simulator in unreal engine, writing some basic websites, designing prototypes for apps and coding basic databases. 
                </p>
                <p>
                    This year I have been mainly working with HTML where I have created webpages that display how people can interact in different ways and also displaying the many different ways that java can be utilized. 
                    In other classes I have been working with SQL and creating databases which then involves adding, altering, and removing sets of data. 
                </p>
                <p>
                  Unfortunately, I no longer have access to the projects that I had created last year as they were linked with my RMIT enducation account which is why i am unable to present the projects on this page. 
                </p>
                <p>
                  Below I have put some basic HTML elements that I have worked with this year to show their functionality.
                </p>
            </div>
            <section class="element-1">
              <H2>HTML elements</H2>
              <table>
                <tr>
                  <th>Roomate name</th>
                  <th>Roomate age</th>
                  <th>Roomate course</th>
                </tr>
                <tr>
                  <td>Cooper Luff</td>
                  <td>19</td>
                  <td>Accounting</td>
                </tr>
                <tr>
                  <td>Grace Willey</td>
                  <td>19</td>
                  <td>Nursing</td>
                </tr>
                <tr>
                  <td>Trent Blake</td>
                  <td>20</td>
                  <td>Teaching</td>
                </tr>
              </table>
              <form>
                <label for="fname">First name:</label><br>
                <input type="text" required v-model="firstname"><br>
                <label for="lname">Last name:</label><br>
                <input type="text" required v-model="lastname"><br>
                <button type="submit">Submit</button>
              </form>
            </section>
            <div class="technology-section">
                <h1>Technologies Studied</h1>
                <div class="logos">
                    <img src="../assets/css-logo.png" alt="Css logo">
                    <img src="../assets/html-logo.png" alt="html logo">
                    <img src="../assets/JavaScript-Logo.png" alt="Javascript logo">
                    <img src="../assets/Python-logo.png" alt="python logo">
                    <img src="../assets/SQL-logo.png" alt="SQL logo">
                    <img src="../assets/unreal-engine-logo.png" alt="Unreal Engine logo">
                </div>
            </div>
            <div class="button-container">
                 <div>
                    <router-link to="/ProjectsCard" v-slot="{navigate}">
                    <button @click="navigate" role="link" class="projects-button">Projects</button>
                    </router-link> 
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}


</script>

<style>
    
</style>
