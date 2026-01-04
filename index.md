---
layout: splash
title: "Clarity is more impressive than complexity."
permalink: /

header:
  overlay_color: "#05060a"
  overlay_filter: "0.8"

excerpt: >
  If your ideas take too long to explain, that’s usually the problem.
  When people tune out, something isn’t clear.
---

<!-- Middle line (fills the awkward space under the hero) -->
<section class="page__content jw-mid">
  <div class="jw-mid__wrap">
    <p class="jw-mid__text">
      You can have a great idea and still lose people. All it takes is a few sloppy lines, a little jargon, and one paragraph that drags.
      People don’t stick around to decode it. They bounce.
    </p>
  </div>

  <style>
    .jw-mid { padding: 0 1.25rem; }
    .jw-mid__wrap { max-width: 900px; margin: 2.25rem auto 0; }
    .jw-mid__text {
      margin: 0;
      text-align: center;
      opacity: 0.95;
      font-size: 1.05rem;
      line-height: 1.7;
    }
  </style>
</section>

<!-- Image + process block -->
<section class="page__content jw-process">
  <div class="jw-process__wrap">
    <div class="jw-process__grid">

      <div class="jw-process__img">
        <img src="/assets/images/jeff01.png" alt="Jeff Whitsitt">
      </div>

      <div class="jw-process__copy">
        <h3 class="jw-process__h">
          Most of my work starts before the writing does.
        </h3>

        <p class="jw-process__steps">
          I ask the questions that sort out what actually matters.<br>
          I organize the message before polishing the language.<br>
          I shape it into writing people can follow.
        </p>
      </div>

    </div>
  </div>

  <style>
    .jw-process { padding: 0 1.25rem; }
    .jw-process__wrap { max-width: 980px; margin: 2.25rem auto 2.5rem; }
    .jw-process__grid {
      display: grid;
      grid-template-columns: 260px minmax(0, 1fr);
      gap: 2.25rem;
      align-items: start;
    }
    .jw-process__img img {
      width: 100%;
      height: auto;
      border-radius: 12px;
      display: block;
    }
    .jw-process__h {
      margin: 0 0 0.85rem 0;
      font-size: 1.65rem;
      line-height: 1.15;
    }
    .jw-process__steps {
      margin: 0;
      line-height: 1.8;
      opacity: 0.95;
      font-size: 1.05rem;
    }

    @media (max-width: 820px) {
      .jw-process__wrap { max-width: 640px; }
      .jw-process__grid { grid-template-columns: 1fr; gap: 1.25rem; }
      .jw-process__img { max-width: 280px; margin: 0 auto; }
      .jw-process__h { font-size: 1.45rem; text-align: center; }
      .jw-process__steps { text-align: center; }
    }
  </style>
</section>

<!-- Fit / Not fit -->
<section class="page__content jw-fit">
  <div class="jw-fit__wrap">
    <div class="jw-fit__grid">

      <div class="jw-fit__col">
        <h3 class="jw-fit__h">This tends to work well for people who:</h3>
        <ul class="jw-fit__list">
          <li>Are good at what they do, but find it hard to explain</li>
          <li>Want their audience to actually pay attention</li>
          <li>Care more about being understood than sounding impressive</li>
        </ul>
      </div>

      <div class="jw-fit__col">
        <h3 class="jw-fit__h">It doesn’t work as well when:</h3>
        <ul class="jw-fit__list">
          <li>Jargon and buzzwords feel necessary</li>
          <li>Word count matters more than the message</li>
          <li>Sounding smart matters more than being understood</li>
        </ul>
      </div>

    </div>
  </div>

  <style>
    .jw-fit { padding: 0 1.25rem; }
    .jw-fit__wrap { max-width: 980px; margin: 0 auto 2.25rem; }
    .jw-fit__grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2.5rem;
      align-items: start;
      border-top: 1px solid rgba(255,255,255,.12);
      padding-top: 2.25rem;
    }
    .jw-fit__h { margin: 0 0 1rem 0; font-size: 1.25rem; }
    .jw-fit__list { margin: 0; line-height: 1.75; }

    @media (max-width: 820px) {
      .jw-fit__wrap { max-width: 640px; }
      .jw-fit__grid { grid-template-columns: 1fr; gap: 1.75rem; }
    }
  </style>
</section>

<!-- Final CTA -->
<section class="page__content jw-cta">
  <div class="jw-cta__wrap">
    <a href="/hire-me/" class="jw-cta__button">
      If this makes sense, let’s talk.
    </a>
  </div>

  <style>
    .jw-cta { padding: 0 1.25rem; }

    .jw-cta__wrap {
      max-width: 980px;
      margin: 0 auto 3rem;
      text-align: center;
      border-top: 1px solid rgba(255,255,255,.12);
      padding-top: 2.25rem;
    }

    .jw-cta__button {
      display: inline-block;
      background: #14c2c2;
      color: #05060a;
      font-size: 1.15rem;
      font-weight: 600;
      padding: 0.9rem 1.75rem;
      border-radius: 8px;
      text-decoration: none;
      transition: transform .15s ease, box-shadow .15s ease, background .15s ease;
      box-shadow: 0 6px 18px rgba(20,194,194,.25);
    }

    .jw-cta__button:hover {
      background: #18d4d4;
      transform: translateY(-1px);
      box-shadow: 0 10px 26px rgba(20,194,194,.35);
    }

    @media (max-width: 640px) {
      .jw-cta__button {
        width: 100%;
        font-size: 1.05rem;
      }
    }
  </style>
</section>
