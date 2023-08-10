<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>shikshit</title>
    <link rel="stylesheet" href="shikshit.css">
    <script src="timer.js"></script>
    <style>
        .min-h-screen {
            min-height: 100vh;
        }

        .bg-red {
            background-color: red;
        }

        .mx-auto {
            margin-left: auto;
            margin-right: auto;
        }

        .flex {
            display: flex;
        }

        .items-center {
            align-items: center;
        }

        .justify-between {
            justify-content: space-between;
        }

        .justify-center {
            justify-content: center;
        }

        .flex-col {
            flex-direction: column;
        }

        .font-bold {
            font-weight: bolder;
        }

        .my-1 {
            margin-top: 13px;
            margin-bottom: 13px;
        }

        .my-2 {
            margin-top: 26px;
            margin-bottom: 26px;
        }

        .px-2 {
            padding-left: 13px;
            padding-right: 13px;
        }

        .text-blue {
            color: rgb(227 74 56);
            ;
        }

        .btn {
            padding: 7px 12px;
            border: 2px solid white;
            border-radius: 6px;
            cursor: pointer;
            color: white;
            background-color: rgb(227 74 56);
            ;
        }

        .overflow-x-hidden {
            overflow-x: hidden;
        }

        .text-center {
            text-align: center;
        }
    </style>
</head>

<body class='overflow-x-hidden'>
    <div class="container mx-auto">
        <header>
            <nav class="flex justify-between">
                <div class="logo font-bold flex items-center text-blue">shikshit Fitness</div>
                <ul class="navbar flex items-center">
                    <li>Home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Contact Us</li>
                    <li><button class="btn">Join Now</button></li>
                </ul>
            </nav>
            <hr>
        </header>
        <main class="min-h-screen">
            <section class="section1">
                <div class="flex">
                    <div class="topleft flex flex-col justify-center px-2">
                        <div class=" text-center">
                            <img class="dumbellimg" src="dumbell.png.jpeg" alt="">
                        </div>
                        <h1 class="my-1 text-center">The best fitness Gym in the town is here</h1>
                        <p class=" text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur
                            error corporis fugit dolore adipisci aperiam omnis nisi dolores hic eius in ex id iure, ea
                            sunt asperiores et voluptatibus dignissimos autem maiores molestias dolor rem delectus
                            quidem! Inventore.</p>
                        <!-- Display the countdown timer in an element -->
                        <p class="deal text-center">The deal ends in <span id="demo"></span></p>
                        <div class="buttons">
                            <button class="btn">Join now</button>
                            <button class="btn">Contact Us</button>
                        </div>
                    </div>
                    <div class="topright flex justify-center">
                        <img class="gymimg" src="gym.jpg" alt="">
                    </div>
                </div>
            </section>
            <hr>
            <section class="section2">
                <h1 class="text-center my-2">Pricing</h1>
                <p class="my-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi debitis provident
                    suscipit temporibus modi voluptatem. Assumenda aspernatur ad nihil quasi expedita eligendi atque?
                    Dolorum eum deserunt dicta iste beatae commodi, doloribus expedita hic recusandae, tempora illum
                    consequuntur? Necessitatibus voluptate animi repellendus reiciendis!</p>
                <div class="boxes flex justify-center">
                    <div class="box">
                        <h2>Free</h2>
                        <ul>
                            <li class="highlighted">₹0/month</li>
                            <li>0 users included</li>
                            <li>2 GB of storage</li>
                            <li>Email support</li>
                            <li>Help center access</li>
                            <li><button class="btn">Signup Now</button></li>
                        </ul>
                    </div>
                    <div class="box">
                        <h2>Pro</h2>
                        <ul>
                            <li class="highlighted">₹150/month</li>
                            <li>0 users included</li>
                            <li>2 GB of storage</li>
                            <li>Email support</li>
                            <li>Help center access</li>
                            <li><button class="btn">Signup Now</button></li>
                        </ul>
                    </div>
                    <div class="box">
                        <h2>Enterprise</h2>
                        <ul>
                            <li class="highlighted">₹500/month</li>
                            <li>0 users included</li>
                            <li>2 GB of storage</li>
                            <li>Email support</li>
                            <li>Help center access</li>
                            <li><button class="btn">Signup Now</button></li>
                        </ul>
                    </div>

                </div>
            </section>
            <hr>
            <section class="section3">
                <h1 class="text-center my-2">Compare Plans</h1>
                <div class="container plantable">
                    <table class="table text-center">
                        <thead>
                            <tr>
                                <th></th>
                                <th>Free</th>
                                <th>Pro</th>
                                <th>Enterprise</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <th scope="row" class="text-start">Public</th>
                                <td>Yes</svg></td>
                                <td>Yes</svg></td>
                                <td>Yes</svg></td>
                            </tr>
                            <tr>
                                <th scope="row" class="text-start">Private</th>
                                <td>-</td>
                                <td>Yes</svg></td>
                                <td>Yes</svg></td>
                            </tr>
                        </tbody>

                        <tbody>
                            <tr>
                                <th scope="row" class="text-start">Permissions</th>
                                <td>Yes</svg></td>
                                <td>Yes</svg></td>
                                <td>Yes</svg></td>
                            </tr>
                            <tr>
                                <th scope="row" class="text-start">Sharing</th>
                                <td>-</td>
                                <td>Yes</svg></td>
                                <td>Yes</svg></td>
                            </tr>
                            <tr>
                                <th scope="row" class="text-start">Unlimited members</th>
                                <td>-</td>
                                <td>Yes</svg></td>
                                <td>Yes</svg></td>
                            </tr>
                            <tr>
                                <th scope="row" class="text-start">Extra security</th>
                                <td>-</td>
                                <td>-</td>
                                <td>Yes</svg></td>
                            </tr>
                        </tbody>
                    </table>
            </section>
            <hr>
        </main>
        <footer>
            Copyright &copy; shikshitFitness.com | All rights reserved
        </footer>

    </div>
</body>

</html>
