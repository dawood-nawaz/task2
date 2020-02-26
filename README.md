<%@ Master Language="C#" AutoEventWireup="true" CodeBehind="touche.master.cs" Inherits="task2.pages.touche" %>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <script src="../js/jquery-2.2.3.min.js"></script>
    <link href="../css/bootstrap.css" rel="stylesheet" />
    <link rel="stylesheet" type="text/css" />
    <script src="../js/bootstrap.js"></script>
    <link href="../css/font-awesome.min.css" rel="stylesheet" />


    <title></title>


    <style>
        body {
            padding: 0;
            margin: 0;
        }

        .header_css {
            width: 100%;
            height: 100vh;
        }

        .nav_css {
            position: fixed;
            width: 100%;
            height:10px;
            padding-left: 6%;
            padding-right: 6%;
            padding-top: 1%;
            
        }

        .ul_css {
            list-style: none;
            overflow: hidden;
            color: #fff;
            padding: 0;
            width: 100%;
            height: 80vh;
        }

        .li_css {
            display: inline-block;
            text-decoration: none;
            padding: 20px;
        }

        .a_css {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 12px;
        }
        .a_css:hover{
            text-decoration:none;
            color:#ffd800;
        }




















        .footer {
            background: #000000;
            padding: 90px;
            
        }

        .header {
            color: #cab541;
            text-transform: uppercase;
        }

        .para {
            color: #9f9b9b;
        }

        .fa {
            color: #9f9b9b;
        }

        .span_F_css {
            color: #9f9b9b;
        }
    </style>






    <asp:ContentPlaceHolder ID="head" runat="server">
    </asp:ContentPlaceHolder>
</head>
<body id="dna">
    <form id="form1" runat="server">













        <div class="wrapper">
            <header class="header_css">
                <nav class="nav_css">

                    <%--<div class="logo">
                        TOUCHE
                    </div>--%>
                    <div class="menu" id="pola">
                        <ul class="ul_css">
                            <li class="li_css"><a href="#" class="a_css">about us </a></li>
                            <li class="li_css"><a href="#" class="a_css">menu </a></li>
                            <li class="li_css"><a href="#" class="a_css">reservation </a></li>

                            <span style="margin-left: 20%; color: #fff; text-transform: uppercase; font-size: 30px; font-family: Playfair Display,serif; font-style: italic;">touche</span>

                            <span style="float: right">
                                <li class="li_css"><a href="#" class="a_css">news and events </a></li>
                                <li class="li_css"><a href="#" class="a_css">gallery </a></li>
                                <li class="li_css"><a href="#" class="a_css">contacts </a></li>
                            </span>
                        </ul>
                    </div>
                </nav>
            </header>





        </div>


        <script type="text/javascript">

            $(document).ready(function () {

                $(window).scroll(function () {

                    var scroll = $(window).scrollTop();
                    if(scroll>90){
                        $("#pola").css("background", "grey");
                        $("#pola").css("height", "65px");
                        
                        console.log(121);
                    }
                    else {
                        $("#pola").css("background", "transparent");
                        console.log(1);
                    }
                })
            });
           
        </script>




        <div>
            <asp:ContentPlaceHolder ID="ContentPlaceHolder1" runat="server">
            </asp:ContentPlaceHolder>
        </div>

        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />

        <br />
        <br />
        <br />







        <%--FOOTER.................................--%>

        <div class="container-fluid footer">
            <div class="row">
                <div class="col-lg-4 col-md-4 col-sm-12">

                    <h6 class="header">about us</h6>
                    <p class="para">
                        dawood nawaz dawood nawaz dawood nawaz dawood nawaz 
                            dawood nawaz dawood nawaz dawood nawaz dawood nawaz 
                            dawood nawaz dawood nawaz dawood nawaz dawood nawaz 
                        <br />
                        <br />
                        @2020 touche.alright reserved.....
                            
                    </p>
                </div>



                <div class="col-lg-4 col-md-4 col-sm-12">
                    <h6 class="header">contact info</h6>
                    <img src="../images/icons/image2.png" width="20" />&nbsp;
                    <span class="span_F_css">1234 GUJRANWALA, PAKISTAN,PK 10027-0000</span><br /><br />

                    <img src="../images/icons/image1.png" width="20" />&nbsp;<span class="span_F_css">+92 000000000000</span><br /><br />

                    <img src="../images/icons/img3.png" width="20" />&nbsp;<span class="span_F_css">admin@gmail.com</span>
                </div>



                <div class="col-lg-4 col-md-4 col-sm-12">
                    <h6 class="header">opening hours</h6>
                    <div style="color: #9f9b9b;">
                        MONDAY - THURSDAY<br />
                        10:00 AM - 11:00 PM
                    </div>

                    <br />
                    <div style="color: #9f9b9b;">
                        FRIDAY - SUNDAY<br />
                        12:00 AM - 3:00 PM
                    </div>
                </div>
            </div>

        </div>


    </form>
</body>
</html>
