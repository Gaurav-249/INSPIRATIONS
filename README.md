
<html>
<head>
	<title>welcome</title>
	<style type="text/css">
		p{
			font-size: 30px;
			border: 8px;
		}
		div{
			text-align: center;
			border: 15px solid: black;
		}
		.myDiv {
  border: 10px outset red;  
  text-align: center;
}
h2{
	font-size: 30px;
	color: mediumseagreen;
	background-color: hotpink;
	}
	      .register .nav-tabs .nav-link:hover {
        border: none;
      }
      .text-align {
        margin-top: -3%;
        margin-bottom: -9%;

        padding: 10%;
        margin-left: 30%;
      }
      .form-new {
        margin-right: 22%;
        margin-left: 20%;
      }
      .register-heading {
        margin-left: 21%;
        margin-bottom: 10%;
        color: #e9ecef;
      }
      .register-heading h1 {
        margin-left: 21%;
        margin-bottom: 10%;
        color: #e9ecef;
      }
      .register {
        background: -webkit-linear-gradient(left, #055a4f, #00c6ff);
        margin-top: 3%;
        padding: 3%;
        border-radius: 2.5rem;
      }
      .btnSubmit {
        width: 50%;
        border-radius: 1rem;
        padding: 1.5%;
        color: #fff;
        background-color: #03612e;
        border: none;
        cursor: pointer;
        margin-right: 6%;
        color: rgb(246, 246, 252);
        margin-top: 4%;
      }

	</style>
</head>
<body>
	<center>
		<h1 style="color: red;background: cyan; font-size: 40px;"><i><marquee behavior="alternate">INSPIRATIONS OF LAYLA MAJNUN</marquee></i></h1> 
		<div>
			<div class="myDiv">
			<fieldset><h2><i><b>IT'S VERY ATTRACTIVE POETRY PLEASE READ IT.</b></i></h2>
		<p style="border-style: double; border-color: purple;" id="p2"><i><b>
			Qays ibn al-Mulawwah was just a boy when he fell deeply in love with Layla Al-Aamiriya. He was sure of this love on the very first day he laid eyes upon her at school. He soon began to write beautiful love poems about Layla and he would read them out loud on street corners to anybody who would care to listen. Such passionate displays of love and devotion caused many to refer to the boy as Majnun, meaning madman.

One day, Majnun found the courage to ask Layla’s father for his daughter’s hand in marriage, but her father refused the request. Such a marriage, the father reasoned, would only cause a scandal. It would not be proper for his daughter to marry a person whom everybody called 'madman'. Instead, Layla was promised to another.

Majnun was overcome with grief and abandoned his home and family and disappeared into the wilderness. He lived a miserable life of solitude among the wild animals, spending his days composing poems to his beloved Layla. Layla was forced to marry another man and, although she did not love him because her heart still belonged to Majnun, she remained a faithful wife.

The news of this marriage was devastating to Majnun who continued to live a life of solitude, refusing to return home to his mother and father in the city.

Majnun’s mother and father missed their son terribly and longed every day for his safe return home. They would leave food for him at the bottom of the garden in the hopes that one day he would come back to them out of the desert. But Majnun remained in the wilderness, writing his poetry in solitude, never speaking to a single soul.</b></i>
		</p>
		 <div class="container register">
      <div class="row">
        <div class="col-md-12">
          <div
            class="tab-pane fade show active text-align form-new"
            id="home"
            role="tabpanel"
            aria-labelledby="home-tab"
          >
            <h3 class="register-heading text-nowrap">HTML Form to WhatsApp</h3>
            <div class="row register-form">
              <div class="col-md-12">
                <form autocomplete="off">
                  <div class="form-group">
                    <input
                      type="text"
                      name="Name"
                      id="name"
                      class="form-control"
                      placeholder="Your Name *"
                      value=""
                      required=""
                    />
                  </div>
                  <div class="form-group">
                    <input
                      type="text"
                      name="Email"
                      id="email"
                      class="form-control"
                      placeholder="Your Email *"
                      value=""
                      required=""
                    />
                  </div>
                  <div class="form-group">
                    <input
                      type="number"
                      name="Phone"
                      id="phone"
                      class="form-control"
                      placeholder="Your Contact Number *"
                      value=""
                      required=""
                    />
                  </div>
                  <div class="form-group">
                    <select class="form-control" id="service">
                      <option>Default select</option>
                      <option>Website Development</option>
                      <option>Mobile App Development</option>
                      <option>Web and Mobile Application</option>
                    </select>
                  </div>
                  <div class="form-group">
                    <input
                      type="submit"
                      name="submit"
                      onclick="gotowhatsapp()"
                      class="btnSubmit btn-block"
                      value="Submit"
                    />
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
<span
class="float"
onclick="gotowhatsapp()"
style="
  position: fixed;
  width: 50px;
  height: 50px;
  bottom: 70px;
  right: 120px;
  color: #fff;
  border-radius: 50px;
  text-align: center;
  cursor: pointer;
  box-shadow: 2px 2px 3px #999;
"
>
<img
  src="https://trickuweb.com/whatsapp.png"
  alt=""
  height="60px"
  width="60px"
/>
</span>
		<button style="background: red;font-size: 20px;" onclick="red()">RED</button>
		<button style="background: skyblue;font-size: 20px;" onclick="skyblue()">SKYBLUE</button>
		<button style="background: pink;font-size: 20px;" onclick="pink()">PINK</button>
		<button style="background: green;font-size: 20px;" onclick="green()">GREEN</button>
		<script type="text/javascript">
			function red()
			{
				document.getElementById('p2').style.color="red"
			}
			function skyblue()
			{
				document.getElementById('p2').style.color="skyblue"
			}
			function pink()
			{
				document.getElementById('p2').style.color="pink"
			}
			function green()
			{
				document.getElementById('p2').style.color="green"
			}
		</script>
		<script>
function gotowhatsapp() {
    
    var name = document.getElementById("name").value;
    var phone = document.getElementById("phone").value;
    var email = document.getElementById("email").value;
    var service = document.getElementById("service").value;

    var url = "https://wa.me/917018392282?text=" 
    + "Name: " + name + "%0a"
    + "Phone: " + phone + "%0a"
    + "Email: " + email  + "%0a"
    + "Service: " + service; 

    window.open(url, '_blank').focus();
}
</script>

    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>

	</fieldset>
</div>

	</div>
	
		</center>

</body>
</html>
