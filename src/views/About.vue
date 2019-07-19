<template>
  <div class="about-card">
    <div class="card-title">
      <img height="50px" src="https://i.ibb.co/55hykPR/profile.png" alt="avatar"
      class="avatar">
      <div class="title-text-content">
        <p>About me</p>
        <h2>Bang Pham</h2>
      </div>
    </div>
    <div class="card-content">
      <p>
					I am a senior at Peachtree Ridge High School. I play lacrosse and cross country. My GPA in school is 3.97. After high school, I wish to attend Georgia Tech and pursue computer science. My hobbies include: fishing, playing video games, and exploring nature.</p>
          <table>
            <tr>
              <th>Interests</th>
              <th>Experience in:</th>
            </tr>
            <tr>
              <td>Design</td>
              <td>Adobe Photoshop, Adobe Illustrator, Canva, Cinema4D</td>
            </tr>
             <tr>
              <td>Coding</td>
              <td>Java, HTML, CSS, JavaScript, Vue.js</td>
            </tr>
            <tr>
              <td>Sports</td>
              <td>Lacrosse, Cross Country, Track and Field</td>
            </tr>
            <tr>
              <td>Extracurriculars</td>
              <td>Volunteering at Atlanta Track Club and Feed My Starving Children, Robotics</td>
            </tr>
             <tr>
              <td>Hobbies</td>
              <td>Fishing, Swimming, Video Games</td>
            </tr>
          </table>

          <p> 
            I am a self-taught graphic designer. In 2015, I began playing around with Photoshop for fun. I kept having fun with it and creating new designs. Eventually, I began doing commissions for designs on the internet as a freelance graphics designer. This only grew my interest even more. While in school, I took a couple classes on graphic design and learned many new skills. Recently, I helped my older brother as an assistant graphic designer for his job.
          </p>

          <p> 
            Growing up, I was always interested in video games, technology, and computers. One day, my brother introduced me to the world of coding. It interested me, so I started teaching myself from YouTube tutorials. I soon realized that this could be a good career path to follow. In my junior year, I was encouraged to take computer science as a class. I enjoyed the class very much and decided to move forward to AP Computer Science in my upcoming senior year.
          </p>

          <div class="contact-wrapper">
            <h3>Contact Me:</h3>
            <p>bangapham16@gmail.com</p>
          </div>

    </div>
  </div>
</template>

<style lang="sass" scoped>
.about-card
  background: #333
  padding: 3em
  border-radius: 10px
  color: white
  .card-title
    display: flex
    align-items: center
    background: #222
    border-radius: 10px
    .avatar
      border: 1px solid rgba(255, 255, 255, 0.4)
      border-radius: 50%
      margin: 0 30px
  .title-text-content
    p
      margin-bottom: 0
      color: rgb(210, 210, 210)
    h2
      margin-top: 0
.card-content p
  line-height: 1.5
  margin: 30px auto

.contact-wrapper
  line-height: 1.5
  margin: 30px auto
table
  border-spacing: 0px
  margin: 50px auto
  tr th, tr td
    border: 1px solid white
    border-top: none
    padding: 10px
    text-align: center
    &:first-of-type
      border-left: none
    &:nth-of-type(2)
      border-right: none
</style>



