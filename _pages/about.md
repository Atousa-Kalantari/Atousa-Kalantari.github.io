---
layout: about
title: about
permalink: /
subtitle: <strong>M.Sc. in Astrophysics | Researcher</strong>

selected_papers: false
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<style>
  .profile-container {
    display: flex;
    align-items: flex-start;
    gap: 2.5rem; 
    margin-top: 1rem;
    margin-bottom: 2rem;
  }
  .profile-image-box {
    flex-shrink: 0;
    width: 240px; 
  }
  .profile-image-box img {
    width: 100%;
    height: 240px;
    object-fit: cover;
    border-radius: 50%; 
  }
  .bio-content {
    flex-grow: 1;
  }
 
  @media (max-width: 768px) {
    .profile-container {
      flex-direction: column;
      align-items: center;
      text-align: left;
    }
  }
</style>

<div class="profile-container">
  <div class="profile-image-box">
    <img src="{{ '/assets/img/prof_pic.png' | relative_url }}" alt="Atousa Kalantari">
  </div>
  <div class="bio-content">

I am an astrophysics researcher interested in applying machine learning to astronomical data, particularly in time-domain astronomy and the study of galaxies.

For my master's thesis, I developed **Microlensify**, a project aimed at detecting microlensing signals in TESS light curves. The work combines light-curve simulations and traditional microlensing fitting methods with a physics-informed, Transformer-based variational autoencoder to distinguish microlensing events from false positives. This research could help improve microlensing detection in current and future astronomical surveys.

I have also worked on estimating galaxy properties, including stellar mass, redshift, and star formation rate, using COSMOS-Web data. This work explores Self-Organizing Maps (SOMs) and K-means clustering as alternatives to traditional spectral energy distribution (SED) fitting methods.

I am currently seeking PhD opportunities in astrophysics, especially in projects involving machine learning and astronomical data analysis.

  </div>
</div>
