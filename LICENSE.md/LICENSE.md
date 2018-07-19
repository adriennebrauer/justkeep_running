<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml" lang="en">
<head runat="server">
    <meta charset="utf-8" />
    <title>Thrive in 5!</title>
    <style>
        #content {
            margin: 30px;
            width: 1000px;
        }
        #vertical1 {
            float: left;
            color: #000000;
            margin-right: 15px;
        }
        #vertical2 {
            float: right;
            color: #000000;
            margin-left: 15px;
        }
        #header {
            font-family: Arial;
            color: #1E90FF;
        }
        .span {
            margin: 7em;
        }
        .span2 {
            margin: 5.7em;

        }
        .pic {
            height: 15%;
            width: 15%;
        }
        
        #thrive {
            text-align: center;
        }
        .pic5 {
            height: 96%;
            width: 96%;
        }
        #thrive2 {
            color:		#1E90FF;
            font-family: Arial;
            font-size: 1.5em;
            text-align: center;
        }
         #schedule {
            float: left;
            width:25%;
            margin-right:20px;
            background-color: #DCDCDC;
            font-family: Arial;
            padding: 17px;
            line-height: 24px;   
        }
        .pic4 {
            width: 100%;
            height: 100%;
            text-align: center;
        }
        .date {
            color: #1E90FF;
            font-family: Hoefler Text;
        }
        .values {
            color: #1E90FF;
            font-family: Hoefler Text;
            font-size: 1.5em;
        }
        #vertical {
                float: left;
                color:	#000000;               
        }
        .pic7 {
            height: 72%;
            width: 72%;
        }
         #itinerary {
            float: left;
            width:60%;
            font-family: Hoefler Text;
            padding-right: 10px;
            padding-left: 20px;        
        }
        .pic2 {
            width:100%;
            height: 100%;
        }
        .header2 {
            color:#1E90FF;
            font-size: 2.9em;
        }
        .blue {
            color:#1E90FF;
            font-size: 1.3em;
        }
        .line {
            border-top: dotted 2px #1E90FF;
        }
        #pic3 {
            height: 83.5%;
            width: 83.5%;
        }
        
        #footer {
            clear: both;
            float: left;
            color:#1E90FF;
            font-family: Arial;
            width: 100%;
            padding-left: 22px;       
        }
        .first {
            text-align: center;    
        }
        .second {
            text-align: left;
        }
        .span3 {
            margin:155px;
        }
    </style>
</head>
<body>
    <form id="form1" runat="server">
        <div id="content">
            <div id="header">
                 <div id="vertical1">
                    <hr width="1" size="2600" />
                 </div> 
                <div id="vertical2">
                    <hr width="1" size="2600" />
                 </div>
                <p>August 1-2, August 8-1<span class="span"></span><img class="pic" src="SEMO.png"/><span class="span2"></span>Moodle Training and On-boarding</p>
               
                <hr/>
            </div>
            <div id="thrive">
               <img class="pic5" src="thrivein5cutout.jpg"/>
                
            </div>
            <div id="thrive2">
                    <p>On-boarding | Excellence in Teaching | Southeast Values</p>
            </div>
                <hr />
            <div id="schedule">
                 
                <h3 class="date">August 1 KL215</h3>
                <hr class="line" />
                <p>Beginning Moodle Training Part 1</p> <a href="https://cstl.semo.edu/event/workshops.aspx?series=Fall%202018%20Institute" target="_blank">sign up here</a>               
                <p>HR Orientation for new Faculty</p>
                <h3 class="date">August 2 KL215</h3>
                <hr class="line" />
                <p>Sexual Harassment Prevention Training</p>
                <p>HR Paperwork for New Hires</p>
                <p>Goose Chase Activity Get to Know the Campus</p>
                <p>University Portraits Taken</p>
                <p>Get Keys, parking passes, IDs, see department heads</p>
                <p>SupportNET Intro Training</p>         
                <img class="pic4" src="thrive5.png"/>
                <h3 class="values">Southeast Values</h3>
                <hr class="line" />
                <p><strong>Student Success</strong>- Southeast Missouri State University values student-centered education adn experiential learning through engaged and adaptive modes in and beyond the classroom in a safe, freindsly, supportive environment tha offers academic and career achievement for our students. <strong>Dr. Carlos Vargas</strong></p>
                <p><strong>Excellence</strong> - Southeast Missouri State University values sustained commitment to quality teaching, service, rsearch, and creative activities integrated into impactful academic and co-curricular programs that offer students a transformative educational experience. <strong>Dr. Hamner Hill</strong></p>
                <p><strong>Access & Diversity</strong> - Southeast Missour State University values access to high quality, affordable education with a broadly representative student body, faculty, and staff that respects and celebrates a diverse learning community in a global society. <strong>Dr. Kristin LaMantia</strong></p>
                <p><strong>Community</strong> - Southeast Missouri State University values an engaged campus learning community committed through shared purposes and service; sustained by respoect, accountability, and adaptability; and astrengthened through collaborative aprtnerships that extend the expertise and saccomplishments of faculty, staff, students, and alumni beyond the campus. <strong>Panel</strong></p>
                <img class="pic7" src="semo6.jpg" />
           </div>
           
           <div id="itinerary">
                <img class="pic2" src="semo1.jpg" />
                <h2 class="header2">New Faculty Conference</h2>
                <h5 class="blue"><em>Wednesday August 8, 8:00-3:00, University Center</em></h5>
                <p>Breakfast 8:00</p>
                <p>Provost Welcome and Inspirational 8:20</p>
                <p>Get to know each other activity 8:50</p>
                <p>Concurrent Session 9:45, 10:45 & 1:00</p>
                <p><span style="margin-left: 3em;">Best Practices of College Teaching</span></p>
                <p><span style="margin-left: 3em;">Work smarter not harder</span></p>
                <p><span style="margin-left: 3em;">Academic Advising</span></p>
                <p><span style="margin-left: 3em;">Tools Session (Office 365; Portal)</span></p>
                <p><span style="margin-left: 3em;">Flexible Teaching</span></p>
                <p>Lunch with Dr. Vargas and his cabinet (Student Success)</p>
                <p>Community and Living in SEMO Panel (Community) 2:00</p>
                <h5 class="blue"><em>Thursday August 9, 8:00-3:00 University Center</em></h5>
                <p>Breakfast <em>(Ecellence)</em> 8:00</p>
                <p>Culturally Responsive Teaching <em>(Access & Diversity) 8:45</em></p>
                <p>Concurrent Sessions @Kent Library 9:45, 10:45               </p>
                <p><span style="margin-left: 3em;">Tour of Library</span></p>
                <p><span style="margin-left: 3em;">Services the Library provides to Faculty</span></p>
                <p>Lunch with the Library Staff</p>
                <p>Who are our students? 1:00</p>
                <p>Past TEW Participants Words of Wisdom 2:00</p>
                <h5 class="blue"><em>Friday August 10, 8:00-2:00 University Center</em></h5>
                <p>Breakfast with Mentors 8:00</p>
                <p>Resource Fair Campus Life 8:30</p>
                <p>Concurrent Session 10:00, 11:00</p>
                <p><span style="margin-left: 3em;">Promotion & Tenure</span></p>
                <p><span style="margin-left: 3em;">Work smarter not harder</span></p>
                <p><span style="margin-left: 3em;">Flexible Teaching</span></p>
                <p><span style="margin-left: 3em;">Designing Teaching Starting from learning Outcomes</span></p>
                <p><span style="margin-left: 3em;">CSTL support for teachers</span></p>
                <p>Dean's Function 12:30</p>
                <div  style="text-align: center">
                    <img id="pic3" src="semo4.jpg" />

                </div>
           </div>
            
           <div id="footer">
               <p class="first">Faculty Development Day Aug 15</p>
               <p class="second">Thrive in 5 <span class="span3"></span>Culturally Responsive Teaching</p>
           </div>

        </div>
    </form>
</body>
</html>
