<script setup>
import LinkedinIcon from './components/icons/LinkedinIcon.vue'
import MailIcon from './components/icons/MailIcon.vue'
import MediumIcon from './components/icons/MediumIcon.vue'
import PhoneIcon from './components/icons/PhoneIcon.vue'
</script>

<template>
  <header>
    <h1>Akshat Trivedi</h1>
    <div class="contacts-wrapper">
      <div class="contacts">
        <PhoneIcon class="contacts-icon" />
        <span>+91 7905737185</span>
      </div>
      <a href="mailto:akshattriv.iit@gmail.com" class="contacts">
        <MailIcon class="contacts-icon" />
        <span>akshattriv.iit@gmail.com</span>
      </a>
      <div class="contacts">
        <LinkedinIcon class="contacts-icon" />
        <a href="https://www.linkedin.com/in/akshat-trivedi-18b8301a5/">akshat-trivedi-18b8301a5</a>
      </div>
      <div class="contacts">
        <MediumIcon class="contacts-icon" />
        <a href="https://medium.com/@akshattriv">@akshattriv</a>
      </div>
    </div>
  </header>
  <main>
    <section class="section">
      <h2 class="section-heading">summary</h2>
      <div class="section-content">
        Software Engineer with approximately 2 years of experience specializing in building Single
        Page Applications (SPAs) from scratch. Proficient in the Vue ecosystem while remaining
        adaptable to various JavaScript frameworks. Demonstrated expertise in delivering
        fast-performing applications with optimized code, adhering to best coding practices.
        Passionate about crafting user-centric experiences and driving innovation in web
        development.
      </div>
    </section>
    <section class="section">
      <h2 class="section-heading">skills</h2>
      <div class="section-bullet-points">
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">Vue JS</span>
        </div>
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">Nuxt JS</span>
        </div>
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">Typescript</span>
        </div>
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">JavaScript</span>
        </div>
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">Sass</span>
        </div>
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">CSS</span>
        </div>
        <div class="bullet-points-wrapper">
          <span class="bullet-points-point"></span>
          <span class="bullet-points">CI/CD & GitHub Actions</span>
        </div>
      </div>
    </section>
    <section class="section">
      <h2 class="section-heading">work experience</h2>
      <div class="section-heading-secondary-wrapper">
        <h3 class="section-heading-secondary">A.P. Moller - Maersk</h3>
        <h3 class="section-heading-secondary">July 2022 - Present</h3>
      </div>
      <h4 class="section-heading-tertiary">Master Data Management Applications</h4>
      <ul class="section-list-wrapper">
        <li class="section-list-item">
          Our team is the part of GDA (Global Data Analytics) and we manage multiple master data. I
          worked on creating a reusable master data management application UI framework, using which
          I delivered 4 master data management applications.
        </li>
        <li class="section-list-item">
          I utilized Vue 3, Vite, Pinia, Vuex, Azure AD for authentication and authorization, and
          Azure Maps in the development of these master data management applications.
        </li>
        <li class="section-list-item">
          Conducted rigorous unit testing with Vitest and adhered to the Test-Driven Development
          (TDD) methodology throughout the development of these applications.
        </li>
        <li class="section-list-item">
          Collaborated closely with stakeholders to understand requirements and translate them into
          functional and user-friendly interfaces across multiple MDM projects.
        </li>
        <li class="section-list-item">
          Ensured high performance and optimized codebase by adhering to best coding practices like
          code-splitting, implementing debouncing, writing re-usable components, composables and
          leveraging Vue ecosystem tools such as Pinia, and Vue Use.
        </li>
        <li class="section-list-item">
          Successfully delivered projects within specified timelines, meeting business objectives
          and enhancing operational efficiency for GDA's MDM initiatives.
        </li>
        <li class="section-list-item">
          Actively participated in code reviews, providing constructive feedback and ensuring code
          quality and consistency throughout the development lifecycle.
        </li>
        <li class="section-list-item">
          Set up Continuous Integration/Continuous Deployment (CI/CD) pipelines to automate testing
          and deployment procedures, ensuring rapid and reliable software delivery.
        </li>
      </ul>
    </section>
    <section class="section">
      <h2 class="section-heading">education</h2>
      <div class="section-content">
        <h5 class="section-content-heading">
          Bachelors of Technology - Computer Science Engineering
        </h5>
        Pranveer Singh Institute of Technology(PSIT), Kanpur - 2022 - 7.79 CGPA
      </div>
      <div class="section-content">
        <h5 class="section-content-heading">Intermediate School</h5>
        Gaurav Memorial International School, Kanpur - 2018 - 69.9%
      </div>
      <div class="section-content">
        <h5 class="section-content-heading">High School</h5>
        Gaurav Memorial International School, Kanpur - 2016 - 7.6 CGPA
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
    letter-spacing: 8px;
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
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    border-left: 6px solid var(--color-background-mute);
    padding-left: 1.2rem;

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
