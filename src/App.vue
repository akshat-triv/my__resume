<script setup>
import LinkedinIcon from './components/icons/LinkedinIcon.vue'
import MailIcon from './components/icons/MailIcon.vue'
import PhoneIcon from './components/icons/PhoneIcon.vue'
</script>

<template>
  <header>
    <h1>Astha Srivastava</h1>
    <div class="contacts-wrapper">
      <div class="contacts">
        <PhoneIcon class="contacts-icon" />
        <span>+91 8707677080</span>
      </div>
      <a href="mailto:vibhutisrivastava62463@gmail.com" class="contacts">
        <MailIcon class="contacts-icon" />
        <span>vibhutisrivastava62463@gmail.com</span>
      </a>
      <div class="contacts">
        <LinkedinIcon class="contacts-icon" />
        <a href="https://www.linkedin.com/in/astha-srivastava-3a0799214/"
          >astha-srivastava-3a0799214</a
        >
      </div>
    </div>
  </header>
  <main>
    <section class="section">
      <h2 class="section-heading">summary</h2>
      <div class="section-content">
        I have served as an Associate Engineer at Nagaro for one year and seven months. My expertise
        lies in quality assurance and ensuring the seamless operation of software through meticulous
        testing and issue resolution. Additionally, I excel in devising comprehensive plans to
        validate software compliance with its specifications. I am seeking an opportunity to further
        expand my skills in a dynamic and challenging environment, contributing to both personal
        career advancement and organizational growth.
      </div>
    </section>
    <section class="section">
      <h2 class="section-heading">skills</h2>
      <div class="section-bullet-points">
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">Manual Testing</span>
        </div>
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">Azure Devops</span>
        </div>
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">Functional Testing</span>
        </div>
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">API Testing</span>
        </div>
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">SQL</span>
        </div>
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">CI/CD</span>
        </div>
      </div>
    </section>
    <section class="section">
      <h2 class="section-heading">professional experience</h2>
      <div class="section-heading-secondary-wrapper">
        <h3 class="section-heading-secondary">Nagarro</h3>
        <h3 class="section-heading-secondary">Aug 2022 - Present</h3>
      </div>
      <h4 class="section-heading-tertiary">Piramal Capital & Housing Finance Limited</h4>
      <ul class="section-list-wrapper">
        <li class="section-list-item">
          Loan Origination System is a lending application that digitizes the loan facility
          generation process, making the entire loan procedure feasible for both employees and
          customers.
        </li>
        <li class="section-list-item">
          Reporting bugs for issues occurring in Production/LIVE and raising observations while
          testing in lower environments.
        </li>
        <li class="section-list-item">
          Performing Smoke Testing, Sanity Testing, Functional Testing, Integration Testing,
          Retesting, Regression Testing, System Testing, UAT, and Compatibility Testing.
        </li>
        <li class="section-list-item">
          Working in Agile, participating in sprint planning and review sessions.
        </li>
        <li class="section-list-item">
          Responsible for writing test scenarios, test cases, and preparing test reports.
        </li>
        <li class="section-list-item">
          Preparing documentation such as Use Cases, Test Scenarios, and Test Cases for Product
          Backlog items and Bugs.
        </li>
      </ul>
      <h4 class="section-heading-tertiary">IXM Cloud Accelerator</h4>
      <ul class="section-list-wrapper">
        <li class="section-list-item">
          It is an internal project on AEM (Adobe Experience Manager) as a CMS (Content Management
          System) tool for developing website content.
        </li>
        <li class="section-list-item">
          Testing the basic components such as content authoring and identifying bugs in the IXM
          website.
        </li>
        <li class="section-list-item">
          Worked on the workflow, Site Translation, Custom Authentication, and Authorization in AEM,
          and performed testing on all of these.
        </li>
        <li class="section-list-item">
          Reviewing the AEM documentation and completing the implementation on Confluence.
        </li>
      </ul>
    </section>
    <section class="section">
      <h2 class="section-heading">education</h2>
      <div class="section-content">
        <h5 class="section-content-heading">
          Bachelors of Technology - Computer Science Engineering
        </h5>
        Pranveer Singh Institute of Technology(PSIT), Kanpur - 2022 - 7.47 SGPA
      </div>
      <div class="section-content">
        <h5 class="section-content-heading">Intermediate School</h5>
        Gaurav Memorial International School, Kanpur - 2018 - 64.8%
      </div>
      <div class="section-content">
        <h5 class="section-content-heading">High School</h5>
        Maa Ananteshwari Vidyalaya(MAV High School), Bilhaur - 2016 - 10 CGPA
      </div>
    </section>
  </main>
</template>

<style lang="scss">
header {
  padding: 2.4rem 4.8rem;
  background-color: var(--color-background-mute);
  margin-bottom: 2.4rem;
}

h1 {
  font-weight: 700;
  margin-bottom: 0.4rem;
  text-transform: uppercase;
  font-size: 3.2rem;
}

.contacts {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: 2rem;
  color: var(--color-text-gray);

  & > * {
    display: block;
  }

  &-icon {
    width: 2.4rem;
    height: 2.4rem;
    color: var(--color-text-gray);

    margin-right: 0.8rem;
  }

  &-wrapper {
    display: flex;
    align-items: center;
  }
}

a:link,
a:visited,
a:active {
  color: var(--color-text);
  text-decoration: none;
  color: var(--color-text-gray);
}

main {
  padding: 0 4.8rem;
}

.section {
  &:not(:last-child) {
    margin-bottom: 2.8rem;
  }

  &-list {
    &-wrapper {
      padding-left: 3.6rem;
      border-left: 6px solid var(--color-background-mute);
    }

    &-item {
      margin-bottom: 0.4rem;
      font-size: 1.6rem;

      &::marker {
        color: var(--color-text-gray);
        font-size: 2rem;
      }
    }
  }

  &-heading {
    font-size: 2.4rem;
    color: var(--color-text-gray);
    font-weight: 600;
    margin-bottom: 0.4rem;
    text-transform: uppercase;

    &-secondary {
      margin-bottom: 0.4rem;
      color: var(--color-text);
      font-size: 2rem;
      font-weight: 700;

      &-wrapper {
        display: flex;
        justify-content: space-between;
        padding-left: 1.2rem;
      }
    }

    &-tertiary {
      margin-bottom: 0.4rem;
      color: var(--color-text-gray);
      font-size: 2rem;
      font-weight: 700;
      padding-left: 2rem;
    }
  }

  &-content {
    padding: 0 1.2rem;
    border-left: 6px solid var(--color-background-mute);

    &:not(:last-child) {
      margin-bottom: 2rem;
    }

    &-heading {
      display: block;
      font-size: 1.6rem;
      font-weight: 700;
    }
  }

  &-bullet-points {
    border-left: 6px solid var(--color-background-mute);
    padding: 0 1.2rem;
    display: flex;
    flex-wrap: wrap;
    align-items: center;

    & > * {
      flex: 0 0 25%;
    }
  }
}

.bullet-points {
  display: inline-block;

  &-wrapper {
    display: flex;
    align-items: center;
    margin-bottom: 1.2rem;
  }

  &-point {
    position: relative;
    display: inline-block;
    width: 0.7rem;
    height: 0.7rem;
    background-color: var(--color-text-gray);
    margin-right: 1.2rem;
    clip-path: circle(50%);
  }
}
</style>
