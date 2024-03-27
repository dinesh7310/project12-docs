<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/20c5629a29.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="travel.css">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
          <a class="navbar-brand" href="#">
            <img
              src="images/travellogo.jpeg"
              class="travel-logo"
            />
          </a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav ml-auto">
              <a class="nav-link active" id="navItem1" href="#wcuSection">
                Home
              </a>
              <a class="nav-link active" href="#packagesSection" id="navItem2">Packages</a>
              <a class="nav-link active" href="#flightBookingSection" id="navItem3">Flight Bookings</a>
              <a class="nav-link active" href="#allPackages">All Packages</a>
              <a class="nav-link active" href="#followus">Follow Us</a>
            </div>
          </div>
        </div>
      </nav>
    <div class="home-section">
      <h1 class="heading">Gogaga Holidays</h1>
        <h1>Plan Your Travel Now!</h1>
        <p>Experience the various exciting tour and travel packages and make hotel reservations,find vacation packages,search cheap hotels and flight tickets</p>

    </div>
    <div id="packagesSection">
      <div class="hotel-booking">
        <h1 class="packages-head"> Tour Packages</h1>
        <input type="search" class="inputValue mt-3" id="name" placeholder="Book your Hotel Now"/>
        <label class="searchValue" for="name">Search</label>
      </div>
        <div class="container">
          <div class="row"> 
          <div class="package-section shadow col-6 mb-3">
            <div class="card-1">
              <div>
                <img src="images/uttaranchal.jpg" class="tour-image">
                <div class="card-body">
                  <i class="bi bi-geo-alt-fill"></i>
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-geo-alt-fill" viewBox="0 0 16 16">
                    <path d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10m0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6"/></svg><p>Naukuchiatal,Mukteshwar,Ranikhet</p>
                  <h1>Grand Uttaranchal Tour Package</h1>
                  <p>6 Nights 7 Days</p>
                </div>
              </div>
            </div>
          </div>
          <div class="package-section shadow col-6 mb-3">
            <div class="card-1">
              <div>
                <img src="images/varanasi.jpg" class="tour-image">
                <div class="card-body">
                  <i class="bi bi-geo-alt-fill"></i>
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-geo-alt-fill" viewBox="0 0 16 16">
                    <path d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10m0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6"/></svg>
                  <p>Varanasi,Bodhgaya,Gaya,Allahabad</p>
                  <h1>Varanasi Bodh Gaya Tour Package</h1>
                  <p>3 Nights 4 Days</p>
                </div>
              </div>
            </div>
          </div>
          <div class="package-section shadow col-6 mb-3">
            <div class="card-1">
              <div class="">
                <img src="images/kashmir.jpg" class="tour-image">
                <div class="card-body">
                  <i class="bi bi-geo-alt-fill"></i>
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-geo-alt-fill" viewBox="0 0 16 16">
                    <path d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10m0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6"/></svg>
                  <p>Nainital,Kausani,Corbett,Haridwar,Mussorie</p>
                  <h1>Haridwar with Mussorie Package</h1>
                  <p>9 Nights 10 Days</p>
                </div>
              </div>
            </div>
          </div>
          <div class="package-section shadow col-6  mb-3">
            <div class="card-1">
              <div class="">
                <img src="images/haridwar.jpeg" class="tour-image">
                <div class="card-body">
                  <i class="bi bi-geo-alt-fill"></i>
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-geo-alt-fill" viewBox="0 0 16 16">
                    <path d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10m0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6"/></svg>
                  <p>Delhi,Haridwar,Rishikesh </p>
                  <h1> Nights Haridwar-Rishikesh Tour Package</h1>
                  <p>3 Nights 4 Days</p>
                </div>
              </div>
            </div>
          </div>  
          </div></div>
      </div>
    </div>
    </div>
    <div id="flightBookingSection">
      <div>
        <div class="flight-section">
          <div class="booking-section">
            <h1>Book a Flight Ticket</h1>
            <hr>
            <h2>Trip Type</h2>
            <div class="trip-type mt-2 ">
              <div><input type="radio" id="round" name="trip">
                <label for="round"> Round Trip</label></div>
              <div><input type="radio" id="oneway" name="trip>
                <label for="oneway"> One Way Trip</label></div>
              <div><input type="radio" id="multi" name="trip>
                <label for="multi"> Multi-Cities Trip</label></div>
            </div>
            <div class="from-to-section mt-2">
              <div>
                <label for="from">From</label>
                <input type="text" class="form-control" id="from">
              </div>
              <div>
                <label for="to"> To</label>
                <input type="text" class="form-control" id="to">
              </div>
            </div>
            <div class="from-to-section">
              <div>
                <label for="airline">AirLine</label>
                <input type="text" class="form-control" id="airline">
              </div>
              <div>
                <label for="departure"> Departure</label>
                <input type="date" class="form-control" id="departure">
              </div>
            </div>
            <button class="btn btn-primary">Save</button>
          </div>
        </div>
      </div>
    </div>
    <div id="allPackages">
      <h1 class="packages-head">Popular Packages</h1>
      <div class="row">
        <div class="col-12 col-md-8">
          <div class="india-tour m-3">
            <p class="package-tour">India Tour Packages</p>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="international-tour m-3">
            <p class="package-tour">International Tour Packages</p>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="Europe-tour m-3">
            <p class="package-tour">Europe Tour Packages</p>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="Educational-tour m-3">
            <p class="package-tour">Educational Tour Packages</p>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="beach-tour m-3">
            <p class="package-tour">Beach Tour Packages</p>
          </div>
        </div>
      </div>
    </div>
    <div id="followus">
      <div class="follow-us-section pt-5 pb-5">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <h1 class="follow-us-section-heading">Follow Us</h1>
            </div>
            <div class="col-12">
              <div class="d-flex flex-row justify-content-center">
                <div class="follow-us-icon-container">
                  <i class="fab fa-twitter icon"></i>
                </div>
                <div class="follow-us-icon-container">
                  <i class="fab fa-instagram icon"></i>
                </div>
                <div class="follow-us-icon-container">
                  <i class="fab fa-facebook icon"></i>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="footer-section pt-5 pb-5">
        <div class="container">
          <div class="row">
            <div class="col-12 text-center">
              <h1 class="footer-section-mail-id">gogagaholidays@.com</h1>
              <p class="footer-section-address">
                Ground floor, Modern Profound Tech park, White Field Rd, Kondapur, Telangana 500084
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
</body>

</html>


.heading{
    color:rgb(1, 21, 235);
    font-size: 55px;
}
.navbar{
    height:12vh;
}
.travel-logo{
    height:80px;
    width:80px;
}
.home-section{
    color:rgb(40, 170, 206);
    font-size: 40px;
    background-image:url("images/effieltower.jpg.jpg");
    background-size:cover;
    width:auto;
    height: 90vh;
    padding:50px;
    display:flex;
    flex-direction: column;
    justify-content:center;
    align-items:center;
    font-family: "Roboto";
}
.packagesSection{
    border-radius:1px;
    padding:30px;
    text-align: center;
}
.packages-head{
    color:black;
    font-size:50px;
    font-family:"Roboto";
    padding:12px;
}
.india-tour{
    background-image: url("images/Indiatour.webp");
    width:780px;
    height:370px;
    margin:10px;
}
.package-tour{
    color:white;
    font-size:38px;
    font-family: "Roboto";
    text-align: center;
}
.international-tour{
    background-image: url("images/Internationaltour.webp");
    width:360px;
    height:370px;
    margin:10px;
    border-radius:10px;
}
.Europe-tour{
    background-image: url("images/Europe-tour.webp");
    width:360px;
    height:370px;
    margin:10px;
    border-radius:10px;
}
.Educational-tour{
    background-image: url("images/Educational-Tour.webp");
    width:360px;
    height:370px;
    margin:10px;
    border-radius:10px;
}
.beach-tour{
    background-image: url("images/beach.jpeg");
    width:360px;
    height:370px;
    margin:10px;
    border-radius:10px;
}
.tour-image{
    width:500px;
    height:380px;
}
.package-section{
    border-radius: 16px;
    border-color: antiquewhite;
    margin:auto;
    padding:auto;
}
.card-1{
    border-radius: 10px;
    font-size:18px;
    overflow: auto;
}
.hotel-booking{
    background-color: rgb(210, 189, 68);
    text-align: center;
    margin: 10px;
    padding:4px;
}
.inputValue{
    font-size: 18px;
    border-style: solid;
    border-width: 1px;
    border-color: #d5cdcd;
    border-radius: 3px;
    padding: 10px;
    width:300px;
    height:60px;
}
.searchValue{
    background-color:black;
    color: white;
    font-size:24px;
    height:60px;
    width:100px;
    border-radius:1px;
}
.footer-section {
    background-color: #0d2436;
}
  .footer-section-mail-id {
    color: #959ead;
    font-family: "Roboto";
    font-weight: bold;
    font-size: 16px;
    margin-top: 20px;
  }
  .footer-section-address {
    color: #959ead;
    font-family: "Roboto";
    font-size: 14px;
  }
  .follow-us-section {
    background-color: white;
  }
  .follow-us-section-heading {
    text-align: center;
    color: #183b56;
    font-family: "Roboto";
    font-size: 28px;
    font-weight: 700;
  }
  .follow-us-icon-container {
    background-color: #faf7e8;
    width: 80px;
    height: 80px;
    border-radius: 40px;
    margin: 15px;
    padding-top: 22px;
    padding-bottom: 14px;
    padding-right: 16px;
    padding-left: 22px;
  }
  .icon {
    color: #d0b200;
    font-size: 35px;
  }
  .flight-section{
    background-color: darksalmon;
    padding:28px;
    font-weight: bold;
  }
  .booking-section{
    background-color: white;
    font-family: "Roboto";
    padding:30px;
  }
  .trip-type{
    display: flex;
    flex-direction:row;
    justify-content:space-around;
    font-size:24px;
  }
  .from-to-section{
    display: flex;
    justify-content:space-around;
  }
  .form-control{
    width:300px;
    height:40px;
  }
 .btn{
    width:130px;
    height:38px;
 }
