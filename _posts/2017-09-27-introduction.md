---
layout: post
title:  "Introduction"
description: A brief introduction about my blog
date:   "2017-09-27 14:30:00 -0900"
tags:
  - personal
categories:
  - personal
slug: introduction
variables:
- name: $timeline-marker-background-color
  value: $white
- name: $timeline-marker-border
  value: .1em solid $grey-light
- name: $timeline-line
  value: .1rem solid $grey-light
- name: $timeline-content-padding
  value: 1em 0 0 2em
- name: $timeline-icon-size
  value: $size-5
- name: $timeline-header-width
  value: 4em
- name: $dimensions
  value: 16 24 32 48 64 96 128
---
<ul class="timeline">
  <li class="timeline-header is-block">
    <span class="tag is-medium is-primary">Start</span>
  </li>
  <li class="timeline-item is-primary">
    <div class="timeline-marker is-primary"></div>
    <div class="timeline-content">
      <p class="heading">January 2016</p>
      <p>Timeline content - Can include any HTML element</p>
    </div>
  </li>
  <li class="timeline-item is-warning">
    <div class="timeline-marker is-warning is-image is-32x32">
      <img src="http://bulma.io/images/placeholders/32x32.png">
    </div>
    <div class="timeline-content">
      <p class="heading">February 2016</p>
      <p>Timeline content - Can include any HTML element</p>
    </div>
  </li>
  <li class="timeline-header is-block">
    <span class="tag is-primary">2017</span>
  </li>
  <li class="timeline-item is-danger">
    <div class="timeline-marker is-danger is-icon">
      <i class="fa fa-flag"></i>
    </div>
    <div class="timeline-content">
      <p class="heading">March 2017</p>
      <p>Timeline content - Can include any HTML element</p>
    </div>
  </li>
  <li class="timeline-header">
    <span class="tag is-medium is-primary">End</span>
  </li>
</ul>
