<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IRCTC Clone App</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        :root {
            --primary: #e74c3c;
            --secondary: #3498db;
            --dark: #2c3e50;
            --light: #ecf0f1;
            --success: #27ae60;
            --warning: #f39c12;
        }
        
        body {
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 500px;
            margin: 0 auto;
            background: white;
            min-height: 100vh;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
            position: relative;
            overflow-x: hidden;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 15px 20px;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .header-top {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .logo {
            display: flex;
            align-items: center;
            font-weight: bold;
            font-size: 1.5rem;
        }
        
        .logo i {
            margin-right: 10px;
            font-size: 1.8rem;
        }
        
        .user-actions a {
            color: white;
            margin-left: 15px;
            font-size: 1.2rem;
        }
        
        .search-container {
            background: white;
            border-radius: 30px;
            padding: 8px 15px;
            display: flex;
            align-items: center;
        }
        
        .search-container input {
            border: none;
            width: 100%;
            padding: 5px 10px;
            outline: none;
            font-size: 1rem;
        }
        
        .search-container button {
            background: transparent;
            border: none;
            color: var(--primary);
            font-size: 1.2rem;
            cursor: pointer;
        }
        
        /* Navigation */
        nav {
            background: white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            padding: 10px 0;
        }
        
        .nav-items {
            display: flex;
            justify-content: space-around;
            list-style: none;
        }
        
        .nav-items li {
            text-align: center;
        }
        
        .nav-items a {
            text-decoration: none;
            color: var(--dark);
            font-size: 0.9rem;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .nav-items i {
            font-size: 1.4rem;
            margin-bottom: 5px;
            color: var(--primary);
        }
        
        /* Main Content */
        .page {
            padding: 20px;
            display: none;
        }
        
        .page.active {
            display: block;
        }
        
        .section-title {
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--light);
            color: var(--dark);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        /* Booking Card */
        .booking-card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.08);
            padding: 20px;
            margin-bottom: 20px;
        }
        
        .input-group {
            margin-bottom: 15px;
            position: relative;
        }
        
        .input-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: 500;
            color: var(--dark);
        }
        
        .input-group input, .input-group select {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 1rem;
            outline: none;
        }
        
        .input-group input:focus, .input-group select:focus {
            border-color: var(--secondary);
        }
        
        .switch-btn {
            position: absolute;
            right: 10px;
            top: 38px;
            background: var(--secondary);
            color: white;
            border: none;
            border-radius: 50%;
            width: 30px;
            height: 30px;
            cursor: pointer;
        }
        
        .btn {
            background: var(--primary);
            color: white;
            border: none;
            padding: 15px;
            border-radius: 8px;
            font-size: 1.1rem;
            font-weight: bold;
            width: 100%;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .btn i {
            margin-right: 10px;
        }
        
        .btn:hover {
            background: #c0392b;
        }
        
        .btn-secondary {
            background: var(--secondary);
        }
        
        .btn-secondary:hover {
            background: #2980b9;
        }
        
        /* Train List */
        .train-item {
            background: white;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.08);
            padding: 15px;
            margin-bottom: 15px;
        }
        
        .train-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 10px;
        }
        
        .train-name {
            font-weight: bold;
            font-size: 1.1rem;
            color: var(--dark);
        }
        
        .train-number {
            color: #777;
            font-size: 0.9rem;
        }
        
        .train-details {
            display: flex;
            justify-content: space-between;
            margin: 10px 0;
            padding: 10px 0;
            border-top: 1px dashed #eee;
            border-bottom: 1px dashed #eee;
        }
        
        .departure, .arrival {
            text-align: center;
            flex: 1;
        }
        
        .time {
            font-size: 1.2rem;
            font-weight: bold;
            color: var(--dark);
        }
        
        .duration {
            text-align: center;
            flex: 1;
            color: #777;
            font-size: 0.9rem;
        }
        
        .train-classes {
            display: flex;
            justify-content: space-between;
            margin-top: 10px;
        }
        
        .class-item {
            text-align: center;
            padding: 8px;
            background: var(--light);
            border-radius: 5px;
            flex: 1;
            margin: 0 5px;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .class-item:hover {
            background: var(--secondary);
            color: white;
        }
        
        .class-name {
            font-weight: 500;
        }
        
        .class-price {
            font-size: 0.9rem;
        }
        
        /* Booking Form */
        .passenger-form {
            margin-bottom: 20px;
        }
        
        .form-row {
            display: flex;
            gap: 15px;
            margin-bottom: 15px;
        }
        
        .form-row .input-group {
            flex: 1;
            margin-bottom: 0;
        }
        
        /* Confirmation Page */
        .confirmation-card {
            text-align: center;
            padding: 30px 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.08);
            margin: 20px 0;
        }
        
        .confirmation-icon {
            width: 80px;
            height: 80px;
            background: var(--success);
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0 auto 20px;
        }
        
        .confirmation-icon i {
            font-size: 2.5rem;
            color: white;
        }
        
        .confirmation-card h2 {
            color: var(--success);
            margin-bottom: 10px;
        }
        
        .booking-details {
            text-align: left;
            margin: 20px 0;
            padding: 15px;
            background: var(--light);
            border-radius: 8px;
        }
        
        .detail-row {
            display: flex;
            justify-content: space-between;
            padding: 8px 0;
            border-bottom: 1px dashed #ddd;
        }
        
        .detail-row:last-child {
            border-bottom: none;
        }
        
        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 0.9rem;
        }
        
        /* Responsive */
        @media (max-width: 480px) {
            .container {
                max-width: 100%;
            }
            
            .form-row {
                flex-direction: column;
                gap: 10px;
            }
            
            .train-classes {
                flex-wrap: wrap;
            }
            
            .class-item {
                flex-basis: 45%;
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="header-top">
                <div class="logo">
                    <i class="fas fa-train"></i>
                    <span>IRCTC</span>
                </div>
                <div class="user-actions">
                    <a href="#" id="loginBtn"><i class="fas fa-user"></i></a>
                    <a href="#"><i class="fas fa-bell"></i></a>
                </div>
            </div>
            <div class="search-container">
                <input type="text" placeholder="Search trains, stations, or more...">
                <button><i class="fas fa-search"></i></button>
            </div>
        </header>
        
        <nav>
            <ul class="nav-items">
                <li>
                    <a href="#" class="nav-link" data-page="home">
                        <i class="fas fa-home"></i>
                        <span>Home</span>
                    </a>
                </li>
                <li>
                    <a href="#" class="nav-link" data-page="book">
                        <i class="fas fa-ticket-alt"></i>
                        <span>Book</span>
                    </a>
                </li>
                <li>
                    <a href="#" class="nav-link" data-page="trains">
                        <i class="fas fa-train"></i>
                        <span>Trains</span>
                    </a>
                </li>
                <li>
                    <a href="#" class="nav-link" data-page="pnr">
                        <i class="fas fa-file-alt"></i>
                        <span>PNR</span>
                    </a>
                </li>
                <li>
                    <a href="#" class="nav-link" data-page="me">
                        <i class="fas fa-user"></i>
                        <span>Me</span>
                    </a>
                </li>
            </ul>
        </nav>
        
        <!-- Home Page -->
        <div id="home" class="page active">
            <h2 class="section-title">Book Ticket</h2>
            <div class="booking-card">
                <div class="input-group">
                    <label for="from">From</label>
                    <input type="text" id="from" placeholder="Source Station" value="New Delhi (NDLS)">
                </div>
                
                <div class="input-group">
                    <label for="to">To</label>
                    <input type="text" id="to" placeholder="Destination Station" value="Mumbai Central (BCT)">
                    <button class="switch-btn"><i class="fas fa-exchange-alt"></i></button>
                </div>
                
                <div class="form-row">
                    <div class="input-group">
                        <label for="date">Date of Journey</label>
                        <input type="date" id="date" value="2023-08-15">
                    </div>
                    
                    <div class="input-group">
                        <label for="class">Class</label>
                        <select id="class">
                            <option>All Classes</option>
                            <option selected>AC First Class (1A)</option>
                            <option>AC 2 Tier (2A)</option>
                            <option>AC 3 Tier (3A)</option>
                            <option>Sleeper (SL)</option>
                        </select>
                    </div>
                </div>
                
                <button class="btn" id="searchTrainsBtn">
                    <i class="fas fa-search"></i> Search Trains
                </button>
            </div>
            
            <h2 class="section-title">Quick Links</h2>
            <div class="form-row">
                <button class="btn btn-secondary">
                    <i class="fas fa-ticket-alt"></i> PNR Status
                </button>
                <button class="btn btn-secondary">
                    <i class="fas fa-train"></i> Live Status
                </button>
            </div>
            
            <h2 class="section-title">Recent Bookings</h2>
            <div class="train-item">
                <div class="train-header">
                    <div class="train-name">Rajdhani Express</div>
                    <div class="train-number">#12951</div>
                </div>
                <div class="train-details">
                    <div class="departure">
                        <div class="time">16:55</div>
                        <div class="station">NDLS</div>
                    </div>
                    <div class="duration">
                        <i class="fas fa-arrow-right"></i><br>
                        15h 30m
                    </div>
                    <div class="arrival">
                        <div class="time">08:25</div>
                        <div class="station">BCT</div>
                    </div>
                </div>
                <div class="train-classes">
                    <div class="class-item">
                        <div class="class-name">1A</div>
                        <div class="class-price">₹4,255</div>
                    </div>
                    <div class="class-item">
                        <div class="class-name">2A</div>
                        <div class="class-price">₹2,470</div>
                    </div>
                    <div class="class-item">
                        <div class="class-name">3A</div>
                        <div class="class-price">₹1,755</div>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Train Search Results Page -->
        <div id="trains" class="page">
            <div class="section-title">
                <span>Available Trains</span>
                <span id="routeInfo">NDLS → BCT | 15 Aug</span>
            </div>
            
            <div class="train-item">
                <div class="train-header">
                    <div class="train-name">Rajdhani Express</div>
                    <div class="train-number">#12951</div>
                </div>
                <div class="train-details">
                    <div class="departure">
                        <div class="time">16:55</div>
                        <div class="station">NDLS</div>
                    </div>
                    <div class="duration">
                        <i class="fas fa-arrow-right"></i><br>
                        15h 30m
                    </div>
                    <div class="arrival">
                        <div class="time">08:25</div>
                        <div class="station">BCT</div>
                    </div>
                </div>
                <div class="train-classes">
                    <div class="class-item">
                        <div class="class-name">1A</div>
                        <div class="class-price">₹4,255</div>
                    </div>
                    <div class="class-item">
                        <div class="class-name">2A</div>
                        <div class="class-price">₹2,470</div>
                    </div>
                    <div class="class-item">
                        <div class="class-name">3A</div>
                        <div class="class-price">₹1,755</div>
                    </div>
                </div>
                <button class="btn" style="margin-top: 15px;">Book Now</button>
            </div>
            
            <div class="train-item">
                <div class="train-header">
                    <div class="train-name">Duronto Express</div>
                    <div class="train-number">#12213</div>
                </div>
                <div class="train-details">
                    <div class="departure">
                        <div class="time">20:40</div>
                        <div class="station">NDLS</div>
                    </div>
                    <div class="duration">
                        <i class="fas fa-arrow-right"></i><br>
                        15h 10m
                    </div>
                    <div class="arrival">
                        <div class="time">11:50</div>
                        <div class="station">BCT</div>
                    </div>
                </div>
                <div class="train-classes">
                    <div class="class-item">
                        <div class="class-name">1A</div>
                        <div class="class-price">₹4,110</div>
                    </div>
                    <div class="class-item">
                        <div class="class-name">2A</div>
                        <div class="class-price">₹2,385</div>
                    </div>
                    <div class="class-item">
                        <div class="class-name">3A</div>
                        <div class="class-price">₹1,695</div>
                    </div>
                </div>
                <button class="btn" style="margin-top: 15px;">Book Now</button>
            </div>
        </div>
        
        <!-- Booking Page -->
        <div id="book" class="page">
            <h2 class="section-title">Passenger Details</h2>
            
            <div class="booking-card">
                <div class="train-header">
                    <div class="train-name">Rajdhani Express #12951</div>
                    <div class="train-number">NDLS → BCT</div>
                </div>
                <div class="train-details">
                    <div class="departure">
                        <div class="time">16:55</div>
                        <div class="station">15 Aug</div>
                    </div>
                    <div class="duration">
                        <i class="fas fa-arrow-right"></i><br>
                        15h 30m
                    </div>
                    <div class="arrival">
                        <div class="time">08:25</div>
                        <div class="station">16 Aug</div>
                    </div>
                </div>
                <div style="text-align: center; margin: 10px 0; font-weight: bold; color: var(--secondary);">
                    AC First Class (1A) | 1 Passenger
                </div>
            </div>
            
            <div class="booking-card">
                <h3 style="margin-bottom: 15px;">Passenger 1 (Adult)</h3>
                
                <div class="form-row">
                    <div class="input-group">
                        <label for="name">Full Name</label>
                        <input type="text" id="name" placeholder="Passenger Name">
                    </div>
                    
                    <div class="input-group">
                        <label for="age">Age</label>
                        <input type="number" id="age" placeholder="Age" min="1" max="100">
                    </div>
                </div>
                
                <div class="form-row">
                    <div class="input-group">
                        <label for="gender">Gender</label>
                        <select id="gender">
                            <option>Male</option>
                            <option>Female</option>
                            <option>Other</option>
                        </select>
                    </div>
                    
                    <div class="input-group">
                        <label for="berth">Berth Preference</label>
                        <select id="berth">
                            <option>No Preference</option>
                            <option>Lower</option>
                            <option>Middle</option>
                            <option>Upper</option>
                            <option>Side Lower</option>
                            <option>Side Upper</option>
                        </select>
                    </div>
                </div>
            </div>
            
            <h2 class="section-title">Payment</h2>
            <div class="booking-card">
                <div class="input-group">
                    <label>Total Amount</label>
                    <div style="font-size: 1.5rem; font-weight: bold; color: var(--primary);">₹4,255.00</div>
                </div>
                
                <div class="input-group">
                    <label for="card">Card Number</label>
                    <input type="text" id="card" placeholder="1234 5678 9012 3456">
                </div>
                
                <div class="form-row">
                    <div class="input-group">
                        <label for="expiry">Expiry Date</label>
                        <input type="text" id="expiry" placeholder="MM/YY">
                    </div>
                    
                    <div class="input-group">
                        <label for="cvv">CVV</label>
                        <input type="text" id="cvv" placeholder="CVV">
                    </div>
                </div>
                
                <button class="btn" id="confirmBookingBtn">
                    <i class="fas fa-check-circle"></i> Confirm Booking
                </button>
            </div>
        </div>
        
        <!-- Confirmation Page -->
        <div id="confirmation" class="page">
            <div class="confirmation-card">
                <div class="confirmation-icon">
                    <i class="fas fa-check"></i>
                </div>
                <h2>Booking Confirmed!</h2>
                <p>Your ticket has been successfully booked.</p>
                <div class="booking-details">
                    <div class="detail-row">
                        <span>PNR Number:</span>
                        <span>8264753190</span>
                    </div>
                    <div class="detail-row">
                        <span>Train:</span>
                        <span>Rajdhani Express #12951</span>
                    </div>
                    <div class="detail-row">
                        <span>From:</span>
                        <span>New Delhi (NDLS)</span>
                    </div>
                    <div class="detail-row">
                        <span>To:</span>
                        <span>Mumbai Central (BCT)</span>
                    </div>
                    <div class="detail-row">
                        <span>Date:</span>
                        <span>15 August 2023</span>
                    </div>
                    <div class="detail-row">
                        <span>Departure:</span>
                        <span>16:55</span>
                    </div>
                    <div class="detail-row">
                        <span>Passenger:</span>
                        <span>1 Adult (1A)</span>
                    </div>
                    <div class="detail-row">
                        <span>Amount Paid:</span>
                        <span style="font-weight: bold; color: var(--primary);">₹4,255.00</span>
                    </div>
                </div>
                <button class="btn" id="homeBtn">
                    <i class="fas fa-home"></i> Back to Home
                </button>
            </div>
        </div>
        
        <footer>
            <p>© 2023 IRCTC - Indian Railway Catering and Tourism Corporation</p>
            <p>Official Rail Booking Partner of Indian Railways</p>
        </footer>
    </div>

    <script>
        // Page Navigation
        document.querySelectorAll('.nav-link').forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                const pageId = this.getAttribute('data-page');
                
                // Hide all pages
                document.querySelectorAll('.page').forEach(page => {
                    page.classList.remove('active');
                });
                
                // Show selected page
                document.getElementById(pageId).classList.add('active');
            });
        });
        
        // Switch stations
        document.querySelector('.switch-btn').addEventListener('click', function() {
            const from = document.getElementById('from').value;
            const to = document.getElementById('to').value;
            
            document.getElementById('from').value = to;
            document.getElementById('to').value = from;
        });
        
        // Search trains button
        document.getElementById('searchTrainsBtn').addEventListener('click', function() {
            // Hide all pages
            document.querySelectorAll('.page').forEach(page => {
                page.classList.remove('active');
            });
            
            // Show trains page
            document.getElementById('trains').classList.add('active');
        });
        
        // Book now buttons
        document.querySelectorAll('.btn').forEach(button => {
            if (button.textContent.includes('Book Now')) {
                button.addEventListener('click', function() {
                    // Hide all pages
                    document.querySelectorAll('.page').forEach(page => {
                        page.classList.remove('active');
                    });
                    
                    // Show booking page
                    document.getElementById('book').classList.add('active');
                });
            }
        });
        
        // Confirm booking
        document.getElementById('confirmBookingBtn').addEventListener('click', function() {
            // Hide all pages
            document.querySelectorAll('.page').forEach(page => {
                page.classList.remove('active');
            });
            
            // Show confirmation page
            document.getElementById('confirmation').classList.add('active');
        });
        
        // Back to home from confirmation
        document.getElementById('homeBtn').addEventListener('click', function() {
            // Hide all pages
            document.querySelectorAll('.page').forEach(page => {
                page.classList.remove('active');
            });
            
            // Show home page
            document.getElementById('home').classList.add('active');
        });
        
        // Set current date as default
        const today = new Date();
        const nextWeek = new Date(today);
        nextWeek.setDate(today.getDate() + 7);
        
        const formattedDate = nextWeek.toISOString().split('T')[0];
        document.getElementById('date').value = formattedDate;
        document.getElementById('date').min = formattedDate;
    </script>
</body>
</html>
