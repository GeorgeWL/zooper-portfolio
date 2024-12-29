<template>
  <AppHeader>About Me</AppHeader>
  <AppMain>
    <Text>If you want to contact me, email me at <a href="mailto:hello@georgewl.dev">hello@georgewl.dev</a> or click on
      to my social media links and say hello.</Text>
    <br /> <br />
    <AppHeadersHeader1>Education</AppHeadersHeader1>

    <AppHeadersHeader2>
      BSc Web Systems Design
    </AppHeadersHeader2>
    <small>
      <AppAnchor href="https://web.archive.org/web/20140703212704/http://www.shu.ac.uk/prospectus/course/487/">Course
        Information
        (archived)
      </AppAnchor>
    </small>
    <br />
    <br />
    <AppHeadersHeader3>Sheffield Hallam University (Sheffield, South Yorkshire, UK)</AppHeadersHeader3>
    <br />
    <Text class="py-3">This is one of the few specialist courses in the UK focused on Web Technologies. Key Areas
      of
      Study:
    </Text>
    <AppUnorderListSpaced>
      <li>HTML5, CSS3</li>
      <li>JavaScript, PHP and ASP web scripting</li>
      <li>User Interface Design</li>
      <li>Programming</li>
      <li>Web Based Systems Architecture</li>
      <li>Web Security</li>
      <li>Creative And Critical Thinking</li>
      <li>Computer Architecture</li>
      <li>Design And Development Of Database Systems</li>
      <li>Computer Networking</li>
      <li>Project Management</li>
      <li>Web Frameworks</li>
      <li>Journal And Thesis Writing</li>
      <li>Information Management (Second year elective)</li>
      <li>Mobile Application Development (Final year elective)</li>
      <li>Cloud Databases And Cloud Computing (Final year elective)</li>
    </AppUnorderListSpaced>
    <br />

    <AppHeadersHeader2>BTEC National Diploma Level 3</AppHeadersHeader2>
    <AppHeadersHeader3>Mid-Cheshire College (Hartford, Cheshire, UK)</AppHeadersHeader3>
    <Text>This course is a strong foundation to build onto with University education or Apprenticeships. Course
      included
      the following modules:</Text>
    <ul>
      <li>Communication and Employability Skills for IT</li>
      <li>Computer Systems</li>
      <li>Information Systems</li>
      <li>Project Planning with IT</li>
      <li>Database Design</li>
      <li>Spreadsheet Modelling</li>
      <li>Customisation of Web Pages</li>
      <li>Software Design and Development</li>
      <li>Human Computer Interaction</li>
      <li>Object Oriented Programming</li>
      <li>Computer Networks</li>
      <li>Website Production</li>
      <li>Event Driven Programming</li>
    </ul>
    <br />
    <AppHeadersHeader2>GCSEs A to C</AppHeadersHeader2>
    <AppHeadersHeader3>Verdin High School</AppHeadersHeader3>
    <Text>All relevant GCSEs to A-C levels.</Text>
  </AppMain>
</template>

<script>
import { AppAnchor, AppHeader, AppHeadersHeader1, AppHeadersHeader2, AppHeadersHeader3, AppMain, AppUnorderListSpaced } from '#components';

const description = "Some more about my life and education.";
useSeoMeta({
  title: "About | George WL",
  description,
});
</script>
