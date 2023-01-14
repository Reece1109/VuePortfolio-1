<template>
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-sm-12 col-md-6 m-auto">
            <h4>Made by Reece Simon &copy; Copyright 2023</h4>
            <ul class="social-links">
              <li><a href="#">Facebook</a></li>
              <li><a href="#">Twitter</a></li>
              <li><a href="#">Instagram</a></li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </template>

  <style>

footer {
      background-color: #242424;
      color: #fff;
      padding: 1rem 0;
      position: relative;
      bottom: 0;
      width: 100%;
    }

    .social-links {
      list-style: none;
      padding: 0;
      display: flex;
    }

    .social-links li {
      margin-right: 1rem;
    }

    .social-links li a {
      color: #fff;
    }

    @media (max-width: 992px) {
      .social-links {
        flex-wrap: wrap;
        justify-content: center;
      }
    }
  </style>
  