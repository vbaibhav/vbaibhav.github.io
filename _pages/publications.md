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

<!-- Fancy Links Section -->
<p>Checkout my publications on:</p>

<p style="display: flex; gap: 15px;">
    <!-- ADS Link -->
    <a href="https://ui.adsabs.harvard.edu/public-libraries/GSi9KwB6TamcOuJGuVaDpw" target="_blank" class="icon-link">
        <span class="icon">
            <i class="ai ai-ads" style="font-size: 20px;"></i>
        </span>
        <span class="text">ADS</span>
    </a>
    <!-- ORCID Link -->
    <a href="https://orcid.org/0000-0002-2536-7752" target="_blank" class="icon-link">
        <span class="icon">
            <i class="ai ai-orcid" style="font-size: 20px;"></i>
        </span>
        <span class="text">ORCID</span>
    </a>
    <!-- Inspire-HEP Link -->
    <a href="https://inspirehep.net/literature?q=f%20a%20baibhav" target="_blank" class="icon-link">
        <span class="icon">
            <i class="ai ai-inspire" style="font-size: 20px;"></i>
        </span>
        <span class="text">Inspire-HEP</span>
    </a>
</p>

<!-- Inline CSS for Fancy Link Styling -->
<style>
    /* Styling for Icon Links */
    .icon-link {
        display: flex;
        align-items: center;
        gap: 8px;
        padding: 8px 15px;
        background-color: transparent; /* Remove background color */
        border: 2px solid transparent; /* Border removed for both light and dark mode */
        color: #333; /* Default text color */
        text-decoration: none;
        border-radius: 8px;
        transition: background-color 0.3s ease, color 0.3s ease, border-color 0.3s ease;
        font-weight: bold;
    }

    /* Hover Effect */
    .icon-link:hover {
        background-color: #007bff; /* Blue background on hover */
        color: #fff; /* Text color change on hover */
        border-color: #007bff; /* Border color changes on hover */
    }

    /* Icon Spacing and Sizing */
    .icon {
        display: inline-block;
    }
    
    .text {
        font-size: 16px;
    }

    /* Dark Mode adjustments (for systems that support dark mode) */
    @media (prefers-color-scheme: dark) {
        .icon-link {
            color: #ddd; /* Lighter text color for dark mode */
            border-color: #444; /* Darker border color */
        }

        .icon-link:hover {
            background-color: #0056b3; /* Darker blue on hover for dark mode */
            border-color: #0056b3;
        }
    }
</style>










{% include bib_search.liquid %}
<div class="publications">

{% bibliography %}

</div>
