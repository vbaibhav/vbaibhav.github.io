---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->


<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/academicons/1.8.6/css/academicons.min.css" rel="stylesheet">

<p>Checkout my publications on:</p>

<p class="publication-links">
    <!-- ADS Link -->
    <a href="https://ui.adsabs.harvard.edu/public-libraries/GSi9KwB6TamcOuJGuVaDpw" target="_blank" class="icon-link">
        <span class="icon">
            <i class="ai ai-ads"></i>
        </span>
        <span class="text">ADS</span>
    </a>
    <!-- ORCID Link -->
    <a href="https://orcid.org/0000-0002-2536-7752" target="_blank" class="icon-link">
        <span class="icon">
            <i class="ai ai-orcid"></i>
        </span>
        <span class="text">ORCID</span>
    </a>
    <!-- Inspire-HEP Link -->
    <a href="https://inspirehep.net/literature?q=f%20a%20baibhav" target="_blank" class="icon-link">
        <span class="icon">
            <i class="ai ai-inspire"></i>
        </span>
        <span class="text">Inspire-HEP</span>
    </a>
</p>

<!-- CSS Styles for Light and Dark Theme -->
<style>
    /* Light Theme Colors (Default) */
    .icon-link {
        display: flex;
        align-items: center;
        gap: 8px;
        padding: 8px 15px;
        background-color: #f0f0f0; /* Light background */
        color: #333; /* Dark text */
        text-decoration: none;
        border-radius: 8px;
        transition: background-color 0.3s ease, color 0.3s ease;
        font-weight: bold;
    }

    /* Dark Theme Colors (When Dark Mode is Active) */
    @media (prefers-color-scheme: dark) {
        .icon-link {
            background-color: #333; /* Dark background */
            color: #f0f0f0; /* Light text */
        }

        .icon-link:hover {
            background-color: #555; /* Darker hover background */
            color: #fff; /* White text on hover */
        }
    }

    /* Hover Effect for Links */
    .icon-link:hover {
        background-color: #007bff; /* Light mode hover background */
        color: #fff; /* White text on hover */
    }

    /* Icon Spacing and Sizing */
    .icon {
        display: inline-block;
        font-size: 20px;
    }

    .text {
        font-size: 16px;
    }

</style>












{% include bib_search.liquid %}
<div class="publications">

{% bibliography %}

</div>
