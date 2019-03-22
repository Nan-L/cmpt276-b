# Udio Project Abstract

Udio is a textbook trading platform designed specifically for University students, and is tested with SFU students on release version.

Sellers can post their used textbook's information on websites, including pictures, quality (conditions) and price of books.

Buyers can purchase books from sellers through website’s listing pages. All books are categorized in listing page, and can be filtered by price or conditions. Listing pages also have a chart of the high, low, and mean prices of past sales for any given books. 

Thus, buyers and sellers will know the accepted prices of the books they are going to purchase/sell. 

## APIs

Logins and profiles of each user are created with Google, Facebook and other APIs, and transactions are handled with Paypal with buyers paying in advance.

## Current status

This project is in final stage of development, for its purpose as a class project.

## How to run

In order to view the app locally, please follow these instructions:
  
Step 0: Initialize Git.

Step 1: Clone the github repository `git clone https://github.com/Nan-L/cmpt276-b/`. 

Step 2: Install Ruby (version 2.5 was used for this project) if you do not have Ruby on your machine.
https://gorails.com/setup/ is a good guide for installation on Ubuntu, MacOS, and Windows systems.

Step 3: Install Bundler gem `gem install bundler`.

Step 4: Install Rails framework (version 5.1 was used for this project)
https://gorails.com/setup/ can be helpful here as well.

Step 5: Run terminal command `bundle install --without production` in the project root directory.

Step 6: Run Puma server (included with Ruby on Rails, via command `bin/rails server`) in the project root directory.

Step 7: Maintain internet connection if working with any of the APIs, as APIs pull information from various internet sources. The website will not work properly if these sources cannot be reached.
