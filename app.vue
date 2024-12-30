<template>
      <div>
        <header>
          <h1>Flow</h1>
          <nav>
            <ul>
              <li><a href="#">Home</a></li>
              <li><a href="#">Profile</a></li>
              <li><a href="#">Messages</a></li>
              <li><a href="#">Notifications</a></li>
            </ul>
          </nav>
        </header>
        <main>
          <NuxtPage />
        </main>
      </div>
    </template>

    <style>
      header {
        background-color: #f8f9fa;
        padding: 20px;
        border-bottom: 1px solid #ddd;
      }

      header h1 {
        margin: 0;
      }

      nav ul {
        list-style: none;
        padding: 0;
      }

      nav ul li {
        display: inline;
        margin-right: 10px;
      }

      nav ul li a {
        text-decoration: none;
        color: #333;
      }

      main {
        padding: 20px;
      }
    </style>
