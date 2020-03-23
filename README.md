# evote-movie-2020-02-all-files-dot-php

Change all content pages from HTML to PHP - so we can add code later...


- change all `.html` file extension to `.php`

- in every page change the navigation links to files ending with `.php`, e.g. the nav for the homepage is now:

  ```php
  <nav>
      <ul>
          <li>
              <a href="index.php">Home</a>
          </li>

          <li>
              <a href="about.php">About Us</a>
          </li>

          <li>
              <a href="list.php" class="current_page">Movie ratings</a>
          </li>

          <li>
              <a href="contact.php">Contact Us</a>
          </li>

          <li>
              <a href="sitemap.php">Site Map</a>
          </li>
      </ul>
  </nav>
  ```

