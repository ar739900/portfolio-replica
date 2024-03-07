<script setup>
</script>

<template>
  <div id="greetings">
    <div id="card-header">
      <img id="face" src="./views/baap.jpg" alt="img.jpg">
      <div id="title">
        <h1 id="name">
          Amit <span id="forestgreen">
            Kumar
          </span>
        </h1>
        <div id="designation">Full stack Developer</div>
        <a href="https://github.com/ar739900" target="_blank"><button id="btn btn-outline-danger">Don't</button></a>
      </div>
      <table>
        <tr>
          <td>Email :</td>
          <td id="forestgreen">ar739900@gmail.com</td>
        </tr>
        <tr>
          <td>Contact :</td>
          <td id="forestgreen">+91 8789998757</td>
        </tr>
        <tr>
          <td>website :</td>
          <td id="forestgreen">example.com</td>
        </tr>
      </table>
    </div>
  </div>
  <div id="card-body">
    <table>
      <tr>
        <td id="tableleft">
          <div id="tableprops">INTRODUCTION</div>
        </td>
        <td id="jobdescription">
          I have honed my skills as a full-stack
          developer through coursework, personal projects, and internships. I am proficient in front-end
          technologies such as HTML, CSS, and JavaScript, as well as back-end frameworks like Node.js and Express.
          With experience in database design, RESTful APIs, and agile development methodologies, I am
          well-equipped to deliver high-quality, scalable solutions that meet business needs.
        </td>
      </tr>
    </table>
    <!-- introduction part end -->
    <!-- work experience part -->
    <table id="marginfix">
      <tr>
        <td id="tableleft">
          <div id="tableprops"> WORK EXPERIENCE</div>
        </td>
        <td>
          <div id="jobdetails">Intern at Suven Consultants</div>
          <div id="jobduration">FROM 2022,Nov. TO 2023</div>
          <div id="jobdescription">Web Developer Intern, ABC Company - Developed and tested responsive
            websites using HTML, CSS, and JavaScript. Collaborated with team members to troubleshoot
            issues and improve site functionality. Gained experience with Git, Express, and MongoDB.</div>
        </td>
      </tr>
      <tr>
        <td></td>
        <td>
          <div id="jobdetails">Worked at abc company</div>
          <div id="jobduration">FROM 20.. TO 20..</div>
          <div id="jobdescription">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa, possimus nam
            sequi et nostrum obcaecati quaerat atque repellat eaque neque pariatur, dolor, sit iure hic iusto
            accusamus id quos fugiat.</div>
        </td>
      </tr>
    </table>
    <!-- work experience part end -->
    <!-- education part -->
    <table id="marginfix">
      <tr>
        <td id="tableleft">
          <div id="tableprops">EDUCATION</div>
        </td>
        <td>
          <div id="jobdetails">Government Polytechnic Banka</div>
          <div id="jobduration">FROM 2016 TO 2019</div>
          <div id="jobdescription">Studied Electrical Engineering.
          </div>
        </td>
      </tr>
      <tr>
        <td></td>
        <td>
          <div id="jobdetails">Lok Nayak Jaiprakash InstiTute of Technology</div>
          <div id="jobduration">FROM 2020 TO 2023</div>
          <div id="jobdescription">Batchlors in Technology in Computer Science and Engineering.</div>
        </td>
      </tr>
    </table>
  </div>
</template>

<style scoped>
body {
  max-width: 100%;
  margin: auto;
}

#card {
  max-width: 50%;
  margin: auto;
  color: #282828;
}

#container {
  background-color: #00b899;

}

#card-header {
  display: flex;
  align-items: center;
}

#face {
  width: 150px;
  height: 150px;
  object-fit: cover;
  border-radius: 75px;
  margin-top: 20px;
}

#title {
  flex: 1;
  margin-left: 20px;
}

#name {
  color: gray;
}

#designation {
  letter-spacing: 1px;
}

#white {
  color: white;
}

#forestgreen {
  color: #00deb8;
}

#card-body {
  background-color: #00deb8;
}

#tableleft {
  width: 200px;
  display: block;
}

#marginfix {
  margin-top: 20px;
}

#tableprops {
  font-size: 20px;
  color: white;
}

#jobdetails {
  font-size: 18px;
}

#jobdetails {
  margin-top: 5px;
}

#jobduration {
  font-size: 13px;
  line-height: 20px;
}

#jobdescription {
  font-size: 14px;
  line-height: 20px;
}

#jobdescription {
  margin-top: 5px;
}
</style>
