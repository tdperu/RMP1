<template>
    <div class="container-fluid m-0 p-0">

        <div id="login-page" class="p-4" style="min-height: 80vh">
            <div class="container pt-3">
                <div class="row pb-5">
                    <div class="col-lg-12 mb-5">   
                        <div class="text-center mb-4">   
                            <h1 class="display-3 text-white">{{ title }}</h1>
                            <h3 class="text-white mt-3 mb-5">Grade Your Grader</h3>
                        </div>

                        <div class="border m-auto w-50 p-3 p-md-3 bg-white rounded shadow">
                            <h2>Login</h2>
                            <form>
                                <div class="form-group p-3">
                                    <!-- <label for="usernametext">Enter your username</label> -->
                                    <input id="usernametext" 
                                             placeholder="Username"
                                             class="form-control"
                                             >
                                </div>
                                <div class="form-group p-3">
                                    <!-- <label for="usernametext">Enter your username</label> -->
                                    <input id="usernametext" 
                                             placeholder="Password"
                                             class="form-control"
                                             >
                                    <button type="submit" class="btn btn-success mt-4">Submit</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div id="about" class="bg-light p-3 p-md-5">
            <div class="row">
                <div class="col-lg">
                    <img src="../assets/icons/classroom-icon.svg" height="120" class="m-4">
                    <h5 class="ml-md-4 mr-md-4">
                        Review the professors that you have had so the teacher and other 
                        students can be see your opinions.
                    </h5>
                </div>
                <div class="col-lg">
                    <img src="../assets/icons/edit-pages-icon.svg" height="120" class="m-4">
                    <h5 class="ml-md-4 mr-md-4">
                        Let others know how much homework the teacher gives and how difficult of a grader
                        they are.
                    </h5>
                </div>
                <div class="col-lg">
                    <img src="../assets/icons/education-group-icon.svg" height="120" class="m-4">
                    <h5 class="ml-md-4 mr-md-4">
                        Graduate knowing you got the most out of school without dealing with those pesky 
                        that catch you by surprise.
                    </h5>
                </div>
            </div>
        </div>

        <!-- <div id="contact" class="bg-info p-4">

        </div> -->


        <div id="footer" class="p-4"> 
            <footer class="text-light p-4">
                <a href="https://www.geneva.edu" target="_blank" class="text-warning">Geneva College</a>
                <br>
                <small>&copy; 2022, Senior Software Project</small>
            </footer>
        </div>

    </div>
  </template>
  
  <script>
  export default {
    name: 'HomePage',
    data () {
      return {
        title: 'Rate My Professor'
      }
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
     #login-page {
        background-color: rebeccapurple;
        background: url('../assets/chalkboard.jpg') no-repeat center center;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        background-size: cover;
     }
     #footer{
        background-color: black ;
     }
     #about {
        min-height: 40vh;
     }
  
  </style>