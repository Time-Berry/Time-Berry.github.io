---
layout: default
title: TIME-BERRY | Beyond the Known
---

<style>

/* =====================================
   TIME-BERRY — HOMEPAGE DESIGN
===================================== */

.tb-home {
  --black: #05070d;
  --navy: #091326;
  --blue: #347cff;
  --cyan: #52d9ff;
  --red: #ff405d;
  --white: #f5f7ff;
  --grey: #9ba9c0;

  color: var(--white);
  font-family: 'Space Grotesk', sans-serif;
}

/* REMOVE DEFAULT SPACING */

.tb-home * {
  box-sizing: border-box;
}

.tb-home section {
  margin: 0;
}

.tb-home a {
  text-decoration: none;
}

/* =====================================
   HERO SECTION
===================================== */

.tb-hero {
  position: relative;
  min-height: 610px;

  display: flex;
  flex-direction: column;
  justify-content: center;

  padding: 85px 35px;

  overflow: hidden;

  background:
    radial-gradient(
      circle at 80% 35%,
      rgba(45, 100, 220, 0.20),
      transparent 35%
    ),
    radial-gradient(
      circle at 15% 85%,
      rgba(255, 55, 85, 0.09),
      transparent 30%
    ),
    linear-gradient(
      140deg,
      #05070d,
      #091326,
      #05070d
    );

  border: 1px solid rgba(90, 140, 255, 0.12);
  border-radius: 18px;
}

.tb-hero::after {
  content: "";
  position: absolute;

  width: 300px;
  height: 300px;

  right: -100px;
  top: 100px;

  border: 1px solid rgba(75, 135, 255, 0.18);
  border-radius: 50%;

  box-shadow:
    0 0 70px rgba(50, 110, 255, 0.10),
    inset 0 0 60px rgba(50, 110, 255, 0.08);

  pointer-events: none;
}

.tb-label {
  color: var(--cyan);

  font-family: 'Orbitron', sans-serif;
  font-size: 12px;

  letter-spacing: 4px;
  font-weight: 600;

  margin-bottom: 28px;
}

.tb-hero h1 {
  font-family: 'Orbitron', sans-serif;

  font-size: clamp(43px, 8vw, 82px);
  line-height: 1.2;

  letter-spacing: -3px;
  font-weight: 800;

  margin: 0 0 25px;

  color: white;
}

.tb-hero h1 span {
  display: block;

  background: linear-gradient(
    100deg,
    #55a1ff,
    #a1caff,
    #ffffff
  );

  -webkit-background-
