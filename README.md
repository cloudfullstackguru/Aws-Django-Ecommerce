# Django eCommerce website using RDS Postgres and deployed on Amazon AWS


<!-- PROJECT LOGO -->
<br />
<p align="center">
    <img src="img/logo_pro.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center"> Complete eCommerce app using Python and Django Framework</h3>

  <p align="center">
    Completely Full stack and fully-featured ecommerce application!
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#Features">Features</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot1]](https://www.linkpicture.com/q/homepage.png)
[![Product Name Screen Shot][product-screenshot2]](https://www.linkpicture.com/q/homepage.png)


#### For deployment ,we will be using AWS Elastic Beanstalk (EB) and AWS S3 Bucket for Static & Media Files Storage

The list of resources that I used for building this project are listed in the acknowledgements.

### Built With

Major frameworks and tools that are used in the project.
* [Django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django)
* [Python](https://www.python.org/)
* [PostgreSQL](https://aws.amazon.com/rds/postgresql/)
* [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
* [Amazon S3](https://aws.amazon.com/s3/)



## Installation


1. First We will Create a virtual environment(virtual environment can be really useful to maintain dependencies of the projects.)
 ```sh
  py -m venv env
   ```
2. Now, activate the virtualenv.(if working in git, the command is below)
 ```sh
 source env/Scripts/activate
   ```
3. Configure the Source Repo 

4. Now, Install all of the packages ( Do for all dependencies are mentioned in requirements.txt)
   ```sh
 pip install -r requirements.txt
   ```
   - We Create a .env file and edit the .env-sample(to secure enough for saving secret values)

5.Let's, Run the development server now. Cheers!
   ```sh
  python manage.py runserver
   ```

<!-- USAGE EXAMPLES -->
## Features

- User Registration, Login with Token Based Verification & Message Alerts
- Did Forgot Password with Secure Validation Links
- Features such as Add to Cart using Session Keys, Increment/decrement/remove Cart Items
- Paginator & Search
- Has Added the Variation in Cart, Grouping Cart Item Variations
- User Account Activation & Activation Link Expiry
- Payment Gateway Integration & Place Order
- Has Orders & Order Number Generation
- Has Review and Rating System
- Has Product Gallery with Unlimited Images
- Has My account for the Customer who can easily edit his profile, profile pictures, change his account password, and also manage his orders.


<!-- CONTRIBUTING -->
## Want to Contribute
Do contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [A Complete Beginner's Guide to Django](https://simpleisbetterthancomplex.com/series/beginners-guide/1.11/)
* [Build an E-commerce Website with Django and Python](https://www.youtube.com/watch?v=YZvRrldjf1Y)
* [Deploying a Django application to Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create-deploy-python-django.html)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot1]: img/esite.png
[product-screenshot2]: img/esite2.png