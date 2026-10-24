<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="S Prerana Priyadarshini: Biostatistician, Statistical Officer and Subject Matter Expert Instructor. Research, education, and experience in population health.">
  <meta name="theme-color" content="#f8f5ee">
  <title>S Prerana Priyadarshini |</title>

  <style>
    :root {
      --ivory: #f8f5ee;
      --paper: #fffdf8;
      --navy: #182d3d;
      --burgundy: #792e43;
      --muted: #52616a;
      --line: #dedbd2;
      --tint: #f0e7e5;
      --serif: Georgia, "Times New Roman", serif;
      --sans: system-ui, -apple-system, "Segoe UI", Arial, sans-serif;
    }

    * { box-sizing: border-box; }

    html {
      scroll-behavior: smooth;
      scroll-padding-top: 6rem;
    }

    body {
      margin: 0;
      background: var(--ivory);
      color: var(--navy);
      font: 16px/1.75 var(--sans);
    }

    a {
      color: var(--burgundy);
      text-underline-offset: 4px;
    }

    a:hover { text-decoration-thickness: 2px; }
    button { font: inherit; }
    [hidden] { display: none !important; }

    :focus-visible {
      outline: 3px solid var(--burgundy);
      outline-offset: 5px;
    }

    ::selection {
      background: #e6c9ce;
      color: var(--navy);
    }

    h1, h2, h3, p { margin-top: 0; }
    h1, h2, h3 { text-wrap: balance; }

    h1, h2 {
      font-family: var(--serif);
      font-weight: 400;
    }

    h2 {
      margin-bottom: 1rem;
      font-size: clamp(2rem, 3.7vw, 3rem);
      line-height: 1.18;
      letter-spacing: -.035em;
    }

    h3 {
      font-size: 1.13rem;
      line-height: 1.5;
    }

    p { margin-bottom: 1.1rem; }

    .wrap {
      width: min(1160px, calc(100% - 80px));
      margin-inline: auto;
    }

    .skip-link {
      position: fixed;
      top: 12px;
      left: 12px;
      z-index: 200;
      padding: 10px 18px;
      background: var(--navy);
      color: white;
      transform: translateY(-160%);
    }

    .skip-link:focus { transform: translateY(0); }

    .site-header {
      position: sticky;
      top: 0;
      z-index: 100;
      border-bottom: 1px solid var(--line);
      background: rgba(248, 245, 238, .97);
    }

    .nav-bar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 24px;
      min-height: 82px;
    }

    .brand {
      display: flex;
      gap: 12px;
      align-items: center;
      color: var(--navy);
      text-decoration: none;
    }

    .brand-mark {
      display: grid;
      place-items: center;
      width: 42px;
      height: 42px;
      border: 1px solid var(--burgundy);
      color: var(--burgundy);
      font: 20px var(--serif);
    }

    .brand-name {
      font-size: .83rem;
      font-weight: 650;
      letter-spacing: .02em;
      line-height: 1.4;
    }

    .brand-name small {
      display: block;
      color: var(--muted);
      font-size: .68rem;
      font-weight: 400;
      letter-spacing: .11em;
      text-transform: uppercase;
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 23px;
      margin: 0;
      padding: 0;
      list-style: none;
    }

    .nav-links a {
      color: var(--navy);
      font-size: .81rem;
      text-decoration: none;
    }

    .nav-links a:hover { color: var(--burgundy); }

    .nav-links .nav-cv {
      padding: 8px 13px;
      border: 1px solid var(--line);
      border-radius: 3px;
    }

    .menu-toggle {
      display: none;
      padding: 7px 12px;
      border: 1px solid var(--line);
      background: var(--paper);
      color: var(--navy);
      border-radius: 3px;
      cursor: pointer;
    }

    .eyebrow {
      margin-bottom: 17px;
      color: var(--burgundy);
      font-size: .7rem;
      font-weight: 700;
      letter-spacing: .17em;
      text-transform: uppercase;
    }

    .hero {
      display: grid;
      grid-template-columns: 1.45fr 1fr;
      align-items: center;
      gap: 70px;
      padding-block: 80px 65px;
    }

    h1 {
      margin-bottom: 20px;
      font-size: clamp(2.25rem, 5.6vw, 4.75rem);
      line-height: 1.08;
      letter-spacing: -.05em;
    }

    h1 span { display: block; }

    .headline {
      margin-bottom: 18px;
      color: var(--burgundy);
      font-size: 1.12rem;
      font-weight: 600;
    }

    .hero-intro {
      max-width: 56ch;
      color: var(--muted);
      font-size: 1.01rem;
    }

    .current-role {
      margin: 25px 0;
      padding-left: 16px;
      border-left: 2px solid var(--burgundy);
      font-size: .84rem;
    }

    .current-role strong {
      display: block;
      font-weight: 600;
    }

    .current-role span { color: var(--muted); }

    .actions {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 11px;
      margin-top: 27px;
    }

    .button {
      display: inline-flex;
      justify-content: center;
      align-items: center;
      gap: 10px;
      min-height: 46px;
      padding: 10px 18px;
      border: 1px solid var(--navy);
      border-radius: 3px;
      color: var(--navy);
      font-size: .79rem;
      font-weight: 600;
      text-decoration: none;
      transition: background .2s, color .2s, transform .2s;
    }

    .button:hover {
      background: var(--navy);
      color: var(--paper);
      transform: translateY(-2px);
    }

    .button-primary {
      border-color: var(--burgundy);
      background: var(--burgundy);
      color: white;
    }

    .button-primary:hover { border-color: var(--navy); }
    .button-text { border-color: transparent; }

    .monogram-frame {
      position: relative;
      display: flex;
      min-height: 415px;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 34px;
      border: 1px solid #d8cfc5;
      background: linear-gradient(145deg, #f2ece2, var(--paper));
      text-align: center;
    }

    .monogram-frame::before,
    .monogram-frame::after {
      content: "";
      position: absolute;
      width: 35px;
      height: 35px;
      border-color: var(--burgundy);
      border-style: solid;
    }

    .monogram-frame::before {
      top: 12px;
      left: 12px;
      border-width: 1px 0 0 1px;
    }

    .monogram-frame::after {
      right: 12px;
      bottom: 12px;
      border-width: 0 1px 1px 0;
    }

    .monogram {
      display: grid;
      place-items: center;
      width: 215px;
      aspect-ratio: 1;
      margin: 8px 0 25px;
      border: 1px solid #b6a49c;
      border-radius: 50%;
      outline: 1px solid #d9ccc1;
      outline-offset: 12px;
      color: var(--burgundy);
      font: 4.3rem var(--serif);
      letter-spacing: -.07em;
    }

    .monogram-caption {
      margin: 12px 0 5px;
      font: 1.4rem/1.4 var(--serif);
    }

    .monogram-note {
      margin: 0;
      color: var(--muted);
      font-size: .65rem;
      letter-spacing: .16em;
      text-transform: uppercase;
    }

    .focus-strip {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 13px 25px;
      padding: 21px 0;
      border-block: 1px solid var(--line);
      color: var(--muted);
      font-size: .74rem;
      letter-spacing: .1em;
      text-transform: uppercase;
    }

    .focus-strip span::before {
      content: "";
      display: inline-block;
      width: 5px;
      height: 5px;
      margin: 0 12px 2px 0;
      background: var(--burgundy);
      border-radius: 50%;
    }

    .section {
      padding-block: 76px;
      border-bottom: 1px solid var(--line);
      scroll-margin-top: 1rem;
    }

    .section-heading {
      max-width: 700px;
      margin-bottom: 33px;
    }

    .section-heading p:last-child {
      margin-bottom: 0;
      color: var(--muted);
    }

    .section-number {
      margin-right: 9px;
      opacity: .75;
    }

    .about-grid {
      display: grid;
      grid-template-columns: .85fr 1.5fr;
      gap: 90px;
    }

    .about-text { color: var(--muted); }
    .about-text p:last-child { margin-bottom: 0; }

    .text-link {
      display: inline-block;
      font-size: .84rem;
      font-weight: 600;
    }

    .interest-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .interest-card {
      padding: 28px 25px;
      border-top: 2px solid var(--burgundy);
      background: var(--paper);
    }

    .interest-index {
      display: block;
      margin-bottom: 24px;
      color: var(--burgundy);
      font: 1.5rem var(--serif);
    }

    .interest-card p {
      margin-bottom: 0;
      color: var(--muted);
      font-size: .9rem;
    }

    .interest-note {
      margin: 22px 0 0;
      color: var(--muted);
      font-size: .85rem;
    }

    .timeline {
      margin: 0;
      padding: 0;
      list-style: none;
    }

    .timeline-item {
      position: relative;
      display: grid;
      grid-template-columns: 105px 1fr;
      gap: 30px;
      padding: 0 0 34px 27px;
      border-left: 1px solid #cdbfc0;
    }

    .timeline-item:last-child { padding-bottom: 0; }

    .timeline-item::before {
      content: "";
      position: absolute;
      top: 8px;
      left: -5px;
      width: 9px;
      height: 9px;
      border-radius: 50%;
      background: var(--burgundy);
      box-shadow: 0 0 0 5px var(--ivory);
    }

    .timeline-year {
      color: var(--burgundy);
      font-size: .91rem;
      font-weight: 650;
    }

    .timeline h3 {
      margin-bottom: 4px;
      font-size: 1.15rem;
    }

    .timeline p {
      margin-bottom: 4px;
      color: var(--muted);
      font-size: .92rem;
    }

    .timeline .grade { font-size: .81rem; }

    .school-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 26px;
      margin-top: 32px;
      padding: 23px 27px;
      background: var(--paper);
      border: 1px solid var(--line);
    }

    .school-grid p {
      margin-bottom: 0;
      color: var(--muted);
      font-size: .83rem;
    }

    .school-grid strong {
      display: block;
      margin-bottom: 5px;
      color: var(--navy);
      font-size: .88rem;
    }

    .project-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 22px;
    }

    .project {
      padding: 29px;
      border: 1px solid var(--line);
      background: var(--paper);
      border-radius: 4px;
      transition: transform .2s, box-shadow .2s;
    }

    .project:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 26px #182d3d09;
    }

    .project-featured {
      grid-column: 1 / -1;
      padding: 34px;
      border-left: 3px solid var(--burgundy);
    }

    .project-meta {
      display: flex;
      flex-wrap: wrap;
      gap: 10px 18px;
      margin-bottom: 13px;
      color: var(--burgundy);
      font-size: .71rem;
      font-weight: 650;
      letter-spacing: .07em;
      text-transform: uppercase;
    }

    .project h3 {
      margin-bottom: 12px;
      font: 1.35rem/1.45 var(--serif);
    }

    .project-featured h3 {
      max-width: 850px;
      font-size: 1.65rem;
    }

    .project p {
      color: var(--muted);
      font-size: .89rem;
    }

    .project .institution {
      font-size: .79rem;
      font-weight: 550;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 7px;
      margin: 16px 0 0;
      padding: 0;
      list-style: none;
    }

    .tags li {
      padding: 4px 10px;
      border: 1px solid #dfd5d3;
      border-radius: 3px;
      color: var(--burgundy);
      background: #faf4f2;
      font-size: .69rem;
      line-height: 1.55;
    }

    .experience {
      padding: 30px;
      border: 1px solid var(--line);
      border-left: 3px solid var(--burgundy);
      background: var(--paper);
    }

    .experience-top {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
      margin-bottom: 15px;
    }

    .date {
      color: var(--burgundy);
      font-size: .79rem;
      font-weight: 650;
    }

    .status {
      padding: 4px 10px;
      border: 1px solid #d3d8cf;
      border-radius: 20px;
      color: #3d583c;
      background: #f1f5ed;
      font-size: .68rem;
    }

    .experience h3 {
      margin-bottom: 6px;
      font-size: 1.3rem;
    }

    .experience .institution {
      margin-bottom: 19px;
      color: var(--muted);
      font-size: .9rem;
    }

    .experience ul {
      margin: 0;
      padding-left: 20px;
      color: var(--muted);
      font-size: .9rem;
    }

    .experience li + li { margin-top: 10px; }

    .community {
      display: grid;
      grid-template-columns: 165px 1fr;
      gap: 22px;
      margin-top: 22px;
      padding: 25px 30px;
      background: var(--tint);
    }

    .community h3 {
      margin-bottom: 7px;
      font-size: 1.02rem;
    }

    .community p {
      margin-bottom: 0;
      color: var(--muted);
      font-size: .88rem;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0 38px;
    }

    .skill-group {
      padding: 22px 0;
      border-top: 1px solid var(--line);
    }

    .skill-group h3 {
      margin-bottom: 10px;
      font-size: .89rem;
    }

    .skill-group ul {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin: 0;
      padding: 0;
      list-style: none;
    }

    .skill-group li {
      padding: 5px 11px;
      border: 1px solid var(--line);
      background: var(--paper);
      font-size: .79rem;
    }

    .language-note {
      margin: 20px 0 0;
      color: var(--muted);
      font-size: .87rem;
    }

    .conference-list {
      margin: 0;
      padding: 0;
      list-style: none;
    }

    .conference {
      display: grid;
      grid-template-columns: 150px 1fr;
      gap: 30px;
      padding-block: 27px;
      border-top: 1px solid var(--line);
    }

    .conference h3 {
      margin-bottom: 10px;
      font: 1.3rem/1.5 var(--serif);
    }

    .conference p {
      margin-bottom: 0;
      color: var(--muted);
      font-size: .87rem;
    }

    .recognition-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 26px;
    }

    .recognition {
      padding: 25px;
      background: var(--paper);
      border: 1px solid var(--line);
    }

    .recognition h3 {
      margin: 12px 0 10px;
      font-size: 1.02rem;
    }

    .recognition p {
      margin: 0;
      color: var(--muted);
      font-size: .84rem;
    }

    .additional {
      margin-top: 25px;
      color: var(--muted);
      font-size: .86rem;
    }

    .additional summary {
      width: fit-content;
      padding: 7px 0;
      color: var(--navy);
      cursor: pointer;
      font-weight: 600;
    }

    .additional ul { padding-left: 22px; }
    .additional li { margin-top: 10px; }

    .contact-section {
      margin-top: 75px;
      padding: 48px;
      border: 1px solid #d4c6c3;
      background: var(--paper);
    }

    .contact-grid {
      display: grid;
      grid-template-columns: 1.2fr 1fr;
      gap: 65px;
      align-items: center;
    }

    .contact-section h2 {
      font-size: clamp(2rem, 3.2vw, 2.6rem);
    }

    .contact-section p {
      color: var(--muted);
      font-size: .93rem;
    }

    .contact-links {
      display: grid;
      gap: 13px;
    }

    .contact-link {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 15px;
      padding: 14px 0;
      border-bottom: 1px solid var(--line);
      color: var(--navy);
      font-size: .9rem;
      text-decoration: none;
      overflow-wrap: anywhere;
    }

    .contact-link:hover { color: var(--burgundy); }

    .contact-link small {
      display: block;
      margin-bottom: 3px;
      color: var(--muted);
      font-size: .66rem;
      letter-spacing: .11em;
      text-transform: uppercase;
    }

    .contact-section .cv-view {
      display: inline-block;
      margin-top: 9px;
      font-size: .82rem;
    }

    .site-footer {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
      gap: 15px;
      padding-block: 30px 35px;
      color: var(--muted);
      font-size: .72rem;
    }

    .site-footer a { color: var(--navy); }

    @keyframes arrive {
      from {
        opacity: 0;
        transform: translateY(12px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @media (prefers-reduced-motion: no-preference) {
      .hero-copy {
        animation: arrive .65s ease-out both;
      }
      .monogram-frame {
        animation: arrive .8s .1s ease-out both;
      }
    }

    @media (max-width: 1050px) {
      .nav-links { gap: 15px; }
      .brand-name { display: none; }
      .hero { gap: 38px; }
      .monogram-frame {
        min-height: 370px;
        padding: 24px;
      }
      .about-grid { gap: 50px; }
    }

    @media (max-width: 800px) {
      .wrap { width: calc(100% - 40px); }

      .nav-bar {
        min-height: 70px;
        flex-wrap: wrap;
        gap: 0;
      }

      .brand-name { display: block; }

      .nav-links {
        flex-wrap: wrap;
        width: 100%;
        gap: 10px 21px;
        padding: 12px 0 20px;
      }

      .nav-links a {
        display: block;
        padding: 6px 0;
        font-size: .9rem;
      }

      .js .menu-toggle { display: inline-flex; }
      .js .nav-links { display: none; }

      .js .nav-links.is-open {
        display: flex;
        flex-direction: column;
        align-items: stretch;
        gap: 2px;
      }

      .js .nav-links .nav-cv {
        display: inline-block;
        margin-top: 8px;
        padding: 8px 12px;
      }

      .hero {
        grid-template-columns: 1fr;
        gap: 38px;
        padding-block: 48px;
      }

      .hero-copy { max-width: 650px; }
      .monogram-frame { min-height: 290px; }

      .monogram {
        width: 145px;
        margin-block: 10px 20px;
        font-size: 3.2rem;
      }

      .monogram-caption { font-size: 1.2rem; }
      .section { padding-block: 52px; }

      .about-grid {
        grid-template-columns: 1fr;
        gap: 22px;
      }

      .about-grid .section-heading { margin: 0; }

      .interest-grid {
        grid-template-columns: 1fr;
        gap: 15px;
      }

      .interest-card { padding: 23px; }
      .interest-index { margin-bottom: 12px; }
      .interest-card h3 { margin-bottom: 9px; }
      .project-grid { grid-template-columns: 1fr; }

      .project-featured {
        grid-column: auto;
        padding: 25px;
      }

      .project { padding: 25px; }
      .project-featured h3 { font-size: 1.4rem; }

      .recognition-grid {
        grid-template-columns: 1fr;
        gap: 15px;
      }

      .community {
        grid-template-columns: 1fr;
        gap: 10px;
        padding: 24px;
      }

      .contact-section {
        margin-top: 52px;
        padding: 28px;
      }

      .contact-grid {
        grid-template-columns: 1fr;
        gap: 15px;
      }

      .contact-section p { margin-bottom: 8px; }
    }

    @media (max-width: 480px) {
      .headline { font-size: 1rem; }
      .hero-intro { font-size: .95rem; }
      .actions { gap: 9px; }

      .button {
        padding-inline: 13px;
        font-size: .75rem;
      }

      .focus-strip {
        justify-content: flex-start;
        gap: 10px 18px;
        font-size: .62rem;
      }

      .focus-strip span::before { margin-right: 8px; }

      .timeline-item {
        grid-template-columns: 1fr;
        gap: 4px;
        padding-left: 22px;
      }

      .school-grid {
        grid-template-columns: 1fr;
        padding: 22px;
        gap: 18px;
      }

      .skills-grid { grid-template-columns: 1fr; }

      .conference {
        grid-template-columns: 1fr;
        gap: 9px;
      }

      .experience { padding: 23px; }
      .experience h3 { font-size: 1.13rem; }
      .contact-section { padding: 25px; }

      .site-footer {
        align-items: flex-start;
        flex-direction: column;
      }
    }

    @media (max-width: 360px) {
      .brand { gap: 8px; }

      .brand-mark {
        width: 36px;
        height: 36px;
        font-size: 17px;
      }

      .brand-name {
        max-width: 130px;
        font-size: .72rem;
      }

      .brand-name small { font-size: .55rem; }

      .menu-toggle {
        padding: 7px 10px;
        font-size: .9rem;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      html { scroll-behavior: auto; }

      *, *::before, *::after {
        animation: none !important;
        transition: none !important;
      }

      .button:hover,
      .project:hover {
        transform: none;
      }
    }

    @media print {
      .site-header,
      .skip-link,
      .actions,
      .monogram-frame,
      .site-footer,
      .additional {
        display: none !important;
      }

      body {
        background: white;
        color: black;
        font-size: 11pt;
      }

      .wrap { width: 100%; }

      .hero,
      .about-grid,
      .contact-grid {
        display: block;
      }

      .hero,
      .section {
        padding-block: 18px;
      }

      .contact-section {
        margin-top: 20px;
        padding: 20px;
      }

      h1 { font-size: 32pt; }
      h2 { font-size: 22pt; }

      .project,
      .experience,
      .recognition {
        break-inside: avoid;
      }

      a { color: inherit; }
    }
  </style>
</head>

<body>
  <a class="skip-link" href="#main">Skip to content</a>

  <header class="site-header">
    <nav class="wrap nav-bar" aria-label="Main navigation">
      <a class="brand" href="#home"
         aria-label="S Prerana Priyadarshini, home">
        <span class="brand-mark" aria-hidden="true">SPP</span>
        <span class="brand-name">
          S Prerana Priyadarshini
          <small>Academic portfolio</small>
        </span>
      </a>

      <button class="menu-toggle"
              type="button"
              aria-controls="primary-nav"
              aria-expanded="false"
              hidden>
        Menu <span aria-hidden="true">☰</span>
      </button>

      <ul class="nav-links" id="primary-nav">
        <li><a href="#about">About</a></li>
        <li><a href="#research">Research</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
        <li>
          <a class="nav-cv"
             href="cv.pdf"
             target="_blank"
             rel="noopener"
             aria-label="View CV, PDF, opens in a new tab">
            View CV <span aria-hidden="true">↗</span>
          </a>
        </li>
      </ul>
    </nav>
  </header>

  <main id="main" tabindex="-1" class="wrap">
    <section class="hero" id="home" aria-labelledby="home-title">
      <div class="hero-copy">
        <p class="eyebrow">
          Biostatistics · Demography · Public health
        </p>

        <h1 id="home-title">
          <span>S Prerana</span>
          <span>Priyadarshini</span>
        </h1>

        <p class="headline">PhD Applicant in Epidemiology</p>

        <p class="hero-intro">
          I bring a background in biostatistics and demography to
          questions about reproductive health, healthcare use, and
          population health in India. I am seeking doctoral training
          in epidemiology to develop this work through rigorous research.
        </p>

        <div class="current-role">
          <strong>
            Statistical Officer and Subject Matter Expert Instructor
          </strong>
          <span>
            Hi-Tech Medical College &amp; Hospital, Bhubaneswar ·
            July 2025–Present
          </span>
        </div>

        <div class="actions">
          <a class="button button-primary" href="#research">
            Explore My Research
            <span aria-hidden="true">↗</span>
          </a>

          <a class="button"
             href="cv.pdf"
             download="S-Prerana-Priyadarshini-CV.pdf">
            Download CV
            <span aria-hidden="true">↓</span>
          </a>

          <a class="button button-text" href="#contact">
            Contact
            <span aria-hidden="true">→</span>
          </a>
        </div>
      </div>

      <div class="monogram-frame">
        <div class="monogram"
             role="img"
             aria-label="SPP, initials of S Prerana Priyadarshini">
          SPP
        </div>

        <p class="monogram-caption">
          Understanding health<br>
          through data.
        </p>

        <p class="monogram-note">
          People · Evidence · Public health
        </p>
      </div>
    </section>

    <div class="focus-strip" aria-label="Academic focus">
      <span>Epidemiology</span>
      <span>Biostatistics</span>
      <span>Demography</span>
      <span>Public health policy</span>
    </div>

    <section class="section about-grid"
             id="about"
             aria-labelledby="about-title">
      <div class="section-heading">
        <p class="eyebrow">
          <span class="section-number" aria-hidden="true">01 /</span>
          About
        </p>

        <h2 id="about-title">
          A foundation in statistics.<br>
          A focus on health.
        </h2>

        <a class="text-link"
           href="cv.pdf"
           target="_blank"
           rel="noopener">
          Read my CV (PDF)
          <span aria-hidden="true">↗</span>
        </a>
      </div>

      <div class="about-text">
        <p>
          I am a biostatistician with an M.Sc. in Biostatistics and
          Demography from the International Institute for Population
          Sciences, Mumbai, and a B.Sc. in Statistics from Ramadevi
          Women’s University, Bhubaneswar.
        </p>

        <p>
          At Hi-Tech Medical College &amp; Hospital, I provide statistical
          advice to institutional and research leadership and guide
          students and researchers in study design, analysis,
          data management, and interpretation.
        </p>

        <p>
          My academic work has examined infertility, teenage marriage
          and pregnancy, antenatal care utilization, and life expectancy
          during the COVID-19 pandemic in India. For doctoral study,
          I want to build on these experiences to investigate population
          health questions with careful statistical analysis and clear
          public health relevance.
        </p>
      </div>
    </section>

    <section class="section"
             id="interests"
             aria-labelledby="interests-title">
      <div class="section-heading">
        <p class="eyebrow">
          <span class="section-number" aria-hidden="true">02 /</span>
          Research interests
        </p>

        <h2 id="interests-title">Questions that guide my work.</h2>

        <p>
          My interests connect epidemiological questions with
          demographic perspectives and statistical methods.
        </p>
      </div>

      <div class="interest-grid">
        <article class="interest-card">
          <span class="interest-index" aria-hidden="true">01</span>
          <h3>Reproductive and maternal health</h3>
          <p>
            Understanding infertility, teenage pregnancy, and antenatal
            care utilization through sociodemographic and
            health-related factors.
          </p>
        </article>

        <article class="interest-card">
          <span class="interest-index" aria-hidden="true">02</span>
          <h3>Population health and demography</h3>
          <p>
            Examining variation in health across populations and
            districts, including changes in life expectancy during
            the COVID-19 pandemic.
          </p>
        </article>

        <article class="interest-card">
          <span class="interest-index" aria-hidden="true">03</span>
          <h3>Statistical methods in epidemiology</h3>
          <p>
            Applying multilevel modeling, multivariate analysis,
            and survival analysis to health research and the
            interpretation of complex data.
          </p>
        </article>
      </div>

      <p class="interest-note">
        My broader interests also include systems biology, healthcare,
        and public health policy.
      </p>
    </section>

    <section class="section"
             id="education"
             aria-labelledby="education-title">
      <div class="section-heading">
        <p class="eyebrow">
          <span class="section-number" aria-hidden="true">03 /</span>
          Education
        </p>
        <h2 id="education-title">Academic preparation.</h2>
      </div>

      <ol class="timeline">
        <li class="timeline-item">
          <time class="timeline-year" datetime="2025">2025</time>
          <div>
            <h3>M.Sc. Biostatistics and Demography</h3>
            <p>
              International Institute for Population Sciences, Mumbai
            </p>
            <p class="grade">CGPA: 7.57</p>
          </div>
        </li>

        <li class="timeline-item">
          <time class="timeline-year" datetime="2023">2023</time>
          <div>
            <h3>B.Sc. Statistics</h3>
            <p>Ramadevi Women’s University, Bhubaneswar</p>
            <p class="grade">CGPA: 9</p>
          </div>
        </li>
      </ol>

      <div class="school-grid">
        <div>
          <strong>
            2020 · All India Senior School Certificate Examination
            (Class XII)
          </strong>
          <p>DAV Public School, Bhubaneswar · 81%</p>
        </div>

        <div>
          <strong>
            2018 · All India Secondary School Examination (Class X)
          </strong>
          <p>DAV Public School, Bhubaneswar · 84.4%</p>
        </div>
      </div>
    </section>

    <section class="section"
             id="research"
             aria-labelledby="research-title">
      <div class="section-heading">
        <p class="eyebrow">
          <span class="section-number" aria-hidden="true">04 /</span>
          Research &amp; projects
        </p>

        <h2 id="research-title">
          Research across reproductive<br>
          and population health.
        </h2>
      </div>

      <div class="project-grid">
        <article class="project project-featured">
          <div class="project-meta">
            <span>Master’s dissertation</span>
            <time datetime="2025">2025</time>
          </div>

          <h3>
            A Regional Perspective on Infertility in India:
            Examining the Role of Sociodemographic, Lifestyle Factors,
            and Non-Communicable Diseases
          </h3>

          <p class="institution">
            International Institute for Population Sciences, Mumbai
          </p>

          <p>
            Examined interrelated sociodemographic, lifestyle,
            and non-communicable disease factors in infertility
            in India, with recommendations for targeted
            reproductive health interventions.
          </p>

          <ul class="tags" aria-label="Dissertation topics">
            <li>Infertility</li>
            <li>Reproductive health</li>
            <li>Sociodemographic factors</li>
            <li>Non-communicable diseases</li>
          </ul>
        </article>

        <article class="project">
          <div class="project-meta">
            <span>Research internship</span>
            <time datetime="2024">2024</time>
          </div>

          <h3>
            Teenage Marriage and Pregnancy in India:
            A District-Level Analysis
          </h3>

          <p class="institution">
            Indian Institute of Public Health,
            Public Health Foundation of India
          </p>

          <p>
            Analyzed NFHS-4 and NFHS-5 datasets to examine
            district-wise teenage pregnancy prevalence in India.
          </p>

          <ul class="tags" aria-label="Internship data and topics">
            <li>NFHS-4 &amp; NFHS-5</li>
            <li>District-level analysis</li>
            <li>Teenage pregnancy</li>
          </ul>
        </article>

        <article class="project">
          <div class="project-meta">
            <span>Summer project</span>
            <time datetime="2023">2023</time>
          </div>

          <h3>
            A National Level Analysis of Life Expectancy Associated
            with the COVID-19 Pandemic in India
          </h3>

          <p class="institution">
            Ramadevi Women’s University, Bhubaneswar
          </p>

          <p>
            Examined life expectancy in India in relation to the
            COVID-19 pandemic, focusing on changes during 2020.
          </p>

          <ul class="tags" aria-label="Summer project topics">
            <li>Life expectancy</li>
            <li>COVID-19</li>
            <li>Population health</li>
          </ul>
        </article>
      </div>
    </section>

    <section class="section"
             id="experience"
             aria-labelledby="experience-title">
      <div class="section-heading">
        <p class="eyebrow">
          <span class="section-number" aria-hidden="true">05 /</span>
          Professional &amp; teaching experience
        </p>

        <h2 id="experience-title">
          Supporting research<br>
          and learning.
        </h2>
      </div>

      <article class="experience">
        <div class="experience-top">
          <span class="date">July 2025–Present</span>
          <span class="status">Current position</span>
        </div>

        <h3>
          Statistical Officer and Subject Matter Expert Instructor
        </h3>

        <p class="institution">
          Hi-Tech Medical College &amp; Hospital (HMCH),
          Bhubaneswar, India
        </p>

        <ul>
          <li>
            Serve as a statistical adviser to the Dean,
            Medical Superintendent, Director, and research leadership,
            supporting research, institutional planning,
            and strategic decision-making.
          </li>
          <li>
            Guide students and researchers in research design,
            statistical analysis, interpretation,
            and scientific communication.
          </li>
          <li>
            Support Family Adaptation Program (FAP) data management
            and evidence-based interpretation.
          </li>
        </ul>
      </article>

      <article class="community">
        <div>
          <span class="date">2026</span>
          <p>Community engagement</p>
        </div>

        <div>
          <h3>Abhinav Surya Trust</h3>
          <p>
            Support program and curriculum development and strategic
            growth initiatives for an NGO focused on improving
            education among India’s indigenous population.
          </p>
        </div>
      </article>
    </section>

    <section class="section"
             id="skills"
             aria-labelledby="skills-title">
      <div class="section-heading">
        <p class="eyebrow">
          <span class="section-number" aria-hidden="true">06 /</span>
          Technical &amp; research skills
        </p>

        <h2 id="skills-title">Tools for quantitative inquiry.</h2>
      </div>

      <div class="skills-grid">
        <div class="skill-group">
          <h3>Statistical software</h3>
          <ul>
            <li>R</li>
            <li>Stata</li>
            <li>SAS</li>
            <li>Python</li>
          </ul>
        </div>

        <div class="skill-group">
          <h3>Data analysis &amp; visualization</h3>
          <ul>
            <li>Power BI</li>
            <li>Advanced Excel</li>
            <li>MLWIN</li>
            <li>CS Pro</li>
            <li>Epi-info</li>
          </ul>
        </div>

        <div class="skill-group">
          <h3>Statistical methods &amp; research areas</h3>
          <ul>
            <li>Multilevel Modeling</li>
            <li>Multivariate Analysis</li>
            <li>Survival Analysis</li>
            <li>Clinical trials</li>
          </ul>
        </div>

        <div class="skill-group">
          <h3>Research practice</h3>
          <ul>
            <li>Study design</li>
            <li>Data management</li>
            <li>Data interpretation</li>
            <li>Scientific communication</li>
            <li>Research mentorship</li>
          </ul>
        </div>
      </div>

      <p class="language-note">
        <strong>Languages:</strong> English, Hindi, Odia
      </p>
    </section>

    <section class="section"
             id="conferences"
             aria-labelledby="conferences-title">
      <div class="section-heading">
        <p class="eyebrow">
          <span class="section-number" aria-hidden="true">07 /</span>
          Conference contributions
        </p>

        <h2 id="conferences-title">
          Sharing research questions<br>
          and approaches.
        </h2>
      </div>

      <ol class="conference-list">
        <li class="conference">
          <time class="date" datetime="2024-12">December 2024</time>

          <div>
            <h3>
              Breaking Barriers or Perpetuating Inequality?
              A Multilevel Logistic Regression Analysis of
              Antenatal Care Utilization in India Using NFHS Data
            </h3>

            <p>
              45th annual conference of the Indian Association
              for the Study of Population (IASP), New Delhi.
            </p>

            <ul class="tags"
                aria-label="Conference contribution methods and topics">
              <li>Multilevel logistic regression</li>
              <li>Antenatal care</li>
              <li>NFHS data</li>
            </ul>
          </div>
        </li>

        <li class="conference">
          <time class="date" datetime="2024-03">March 2024</time>

          <div>
            <h3>
              Discerning the Impact of COVID-19 Pandemic
              on Life Expectancy in India
            </h3>

            <p>
              Conference paper for the National Seminar on
              Data Driven Predictive Analytics &amp; Modeling-2024
              (DDPAM-2024), Sambalpur University, Odisha.
            </p>
          </div>
        </li>
      </ol>
    </section>

    <section class="section"
             id="recognition"
             aria-labelledby="recognition-title">
      <div class="section-heading">
        <p class="eyebrow">
          <span class="section-number" aria-hidden="true">08 /</span>
          Fellowship, qualifications &amp; training
        </p>

        <h2 id="recognition-title">
          Continuing academic development.
        </h2>
      </div>

      <div class="recognition-grid">
        <article class="recognition">
          <span class="date">2023–2025</span>
          <h3>Institute Fellowship</h3>
          <p>
            Fellowship for M.Sc. studies at the International
            Institute for Population Sciences (IIPS), Mumbai.
          </p>
        </article>

        <article class="recognition">
          <span class="date">2025</span>
          <h3>UGC-NET qualification</h3>
          <p>
            Qualified the All-India UGC-NET examination for
            eligibility for PhD programs in India.
          </p>
        </article>

        <article class="recognition">
          <span class="date">2022</span>
          <h3>National Training Program on Official Statistics</h3>
          <p>
            Represented Odisha in the program organized by the
            National Statistical System Training Academy (NSSTA),
            Greater Noida.
          </p>
        </article>
      </div>

      <details class="additional">
        <summary>Additional academic activities</summary>
        <ul>
          <li>
            <strong>2022:</strong>
            Represented Ramadevi Women’s University in National Quiz
            competitions on Official Statistics organized by the
            National Statistical Office, Ministry of Statistics
            and Program Implementation.
          </li>

          <li>
            <strong>2023:</strong>
            Participated in a Physics and Data Science seminar
            organized by Homi Bhabha National Institute and the
            Institute of Physics, Bhubaneswar.
          </li>

          <li>
            <strong>2026:</strong>
            Qualified the IELTS Academic examination.
          </li>
        </ul>
      </details>
    </section>

    <section class="contact-section"
             id="contact"
             aria-labelledby="contact-title">
      <div class="contact-grid">
        <div>
          <p class="eyebrow">Contact</p>
          <h2 id="contact-title">Let’s discuss research.</h2>

          <p>
            I welcome conversations with potential supervisors
            and research groups about doctoral study in epidemiology
            and related population health research.
          </p>

          <a class="cv-view"
             href="cv.pdf"
             target="_blank"
             rel="noopener">
            View CV (PDF, opens in a new tab)
            <span aria-hidden="true">↗</span>
          </a>
        </div>

        <div class="contact-links">
          <a class="contact-link"
             href="mailto:preranap274@gmail.com">
            <span>
              <small>Email</small>
              preranap274@gmail.com
            </span>
            <span aria-hidden="true">↗</span>
          </a>

          <a class="contact-link"
             href="https://www.linkedin.com/in/prerana-priyadarshini"
             target="_blank"
             rel="noopener noreferrer"
             aria-label="S Prerana Priyadarshini on LinkedIn, opens in a new tab">
            <span>
              <small>Professional profile</small>
              LinkedIn
            </span>
            <span aria-hidden="true">↗</span>
          </a>
        </div>
      </div>
    </section>
  </main>

  <footer class="wrap site-footer">
    <span>
      © <span id="year">2026</span> S Prerana Priyadarshini
    </span>

    <span>Epidemiology · Biostatistics · Demography</span>

    <a href="#home">
      Back to top <span aria-hidden="true">↑</span>
    </a>
  </footer>

  <script>
    (function () {
      'use strict';

      var toggle = document.querySelector('.menu-toggle');
      var nav = document.getElementById('primary-nav');

      function closeMenu() {
        toggle.setAttribute('aria-expanded', 'false');
        nav.classList.remove('is-open');
      }

      toggle.hidden = false;
      document.documentElement.classList.add('js');

      toggle.addEventListener('click', function () {
        var open = toggle.getAttribute('aria-expanded') !== 'true';

        toggle.setAttribute('aria-expanded', String(open));
        nav.classList.toggle('is-open', open);
      });

      nav.addEventListener('click', function (event) {
        if (event.target.closest('a')) {
          closeMenu();
        }
      });

      document.addEventListener('keydown', function (event) {
        if (
          event.key === 'Escape' &&
          toggle.getAttribute('aria-expanded') === 'true'
        ) {
          closeMenu();
          toggle.focus();
        }
      });

      window.addEventListener('resize', function () {
        if (window.innerWidth > 800) {
          closeMenu();
        }
      });

      document.getElementById('year').textContent =
        String(new Date().getFullYear());
    }());
  </script>
</body>
</html># new
