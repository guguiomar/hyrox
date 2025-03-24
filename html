<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>HYROX Training Planner</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=SF+Pro+Display:wght@300;400;500;600&display=swap">
    <style>
        body {
            font-family: 'SF Pro Display', -apple-system, BlinkMacSystemFont, sans-serif;
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
            background-color: #000;
            color: #fff;
            line-height: 1.5;
            -webkit-font-smoothing: antialiased;
            letter-spacing: -0.02em;
        }
        .container {
            background: linear-gradient(145deg, #111 0%, #0a0a0a 100%);
            padding: 60px;
            border-radius: 30px;
            box-shadow: 0 30px 60px rgba(0,0,0,0.4);
            backdrop-filter: blur(20px);
        }
        .title-container {
            text-align: center;
            margin-bottom: 60px;
        }
        h1 {
            color: #FFCB00;
            font-size: 4em;
            font-weight: 700;
            letter-spacing: -0.03em;
            margin-bottom: 15px;
            line-height: 1.1;
            background: linear-gradient(135deg, #FFCB00 0%, #FFA500 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 2px 30px rgba(255,203,0,0.3);
        }
        .subtitle {
            color: rgba(255,255,255,0.7);
            font-size: 1.5em;
            font-weight: 400;
            letter-spacing: 0.02em;
            margin: 0;
            text-transform: uppercase;
        }
        h2 {
            color: #FFCB00;
            font-size: 2em;
            font-weight: 500;
            margin-top: 60px;
            margin-bottom: 30px;
            letter-spacing: -0.02em;
        }
        .input-group {
            margin-bottom: 35px;
            transition: transform 0.2s ease;
        }
        .input-group:hover {
            transform: translateX(5px);
        }
        label {
            display: block;
            margin-bottom: 12px;
            color: rgba(255,203,0,0.9);
            font-weight: 400;
            font-size: 0.95em;
            letter-spacing: 0.02em;
        }
        input, select, textarea {
            width: 100%;
            padding: 16px;
            margin-top: 8px;
            background: rgba(255,255,255,0.05);
            border: 1px solid rgba(255,255,255,0.1);
            border-radius: 12px;
            color: #fff;
            font-size: 16px;
            backdrop-filter: blur(10px);
            transition: all 0.3s ease;
        }
        input:focus, select:focus, textarea:focus {
            outline: none;
            border-color: #FFCB00;
            box-shadow: 0 0 0 2px rgba(255,203,0,0.2);
        }
        button {
            background: linear-gradient(135deg, #FFCB00 0%, #FFB800 100%);
            color: #000;
            padding: 18px 36px;
            border: none;
            border-radius: 14px;
            cursor: pointer;
            font-weight: 600;
            letter-spacing: -0.01em;
            transition: all 0.4s cubic-bezier(0.16, 1, 0.3, 1);
            font-size: 16px;
            position: relative;
            overflow: hidden;
        }
        button:hover {
            transform: translateY(-2px) scale(1.02);
            box-shadow: 0 20px 40px rgba(255,203,0,0.2);
        }
        button:active {
            transform: translateY(1px) scale(0.98);
        }
        .plan-output {
            margin-top: 40px;
            white-space: pre-wrap;
            background: rgba(255,255,255,0.03);
            padding: 30px;
            border-radius: 20px;
            border-left: 4px solid #FFCB00;
            font-family: 'SF Mono', monospace;
            line-height: 1.6;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        .format-info {
            background: rgba(255,255,255,0.02);
            padding: 35px;
            border-radius: 20px;
            margin: 30px 0;
            border: 1px solid rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            transition: all 0.3s ease;
        }
        .format-info:hover {
            background: rgba(255,255,255,0.03);
            transform: translateY(-5px);
        }
        .format-info ul, .format-info ol {
            margin: 15px 0;
            padding-left: 25px;
            color: #ddd;
        }
        #categoryDetails {
            color: #ddd;
            line-height: 1.6;
        }
        .plan-output h3 {
            color: #FFCB00;
            font-size: 1.5em;
            font-weight: 600;
            margin-top: 30px;
            margin-bottom: 15px;
        }
        .plan-output ul, .plan-output ol {
            margin: 15px 0;
            padding-left: 25px;
            color: #ddd;
        }
        .plan-output li {
            line-height: 1.8;
        }
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }
            .container {
                padding: 20px;
            }
            button {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="title-container">
            <h1>HYROX AI Coach</h1>
            <p class="subtitle">Personalized HYROX Programming</p>
        </div>
        <!-- User Information -->
        <h2>Personal Information</h2>
        <div class="input-group">
            <label>Age:</label>
            <input type="number" id="userAge" min="16" max="100">
        </div>
        <div class="input-group">
            <label>Gender:</label>
            <select id="userGender">
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
        </div>
        <div class="input-group">
            <label>Weight (kg):</label>
            <input type="number" id="userWeight" step="0.1">
        </div>
        <div class="input-group">
            <label>Height (cm):</label>
            <input type="number" id="userHeight">
        </div>
        <!-- HYROX Category Selection -->
        <h2>HYROX Category</h2>
        <div class="input-group">
            <label>Select your category:</label>
            <select id="hyroxCategory">
                <option value="pro">HYROX PRO (Individual)</option>
                <option value="open">HYROX OPEN (Individual)</option>
                <option value="proDoubles">HYROX PRO Doubles</option>
                <option value="openDoubles">HYROX OPEN Doubles</option>
                <option value="relay">HYROX Relay</option>
            </select>
        </div>
        <!-- Competition Planning -->
        <div class="input-group">
            <label>Training Purpose:</label>
            <select id="trainingPurpose">
                <option value="base">Building Base Fitness</option>
                <option value="competition">Preparing for Competition</option>
            </select>
        </div>
        <div class="input-group" id="competitionDateGroup" style="display: none;">
            <label>Competition Date:</label>
            <input type="date" id="competitionDate">
        </div>
        <!-- HYROX Format -->
        <h2>HYROX Race Format</h2>
        <div class="format-info">
            <p>Selected category weights and requirements will be shown here based on your selection.</p>
            <div id="categoryDetails"></div>
        </div>
        <!-- Initial Setup -->
        <div class="input-group">
            <label>Current 1km Time (minutes:seconds):</label>
            <input type="text" id="currentPace" placeholder="5:05">
        </div>
        <div class="input-group">
            <label>Weekly Availability (sessions):</label>
            <select id="availability">
                <option value="3">3 sessions</option>
                <option value="4">4 sessions</option>
                <option value="5">5 sessions</option>
                <option value="6">6 sessions</option>
                <option value="7">7 sessions</option>
            </select>
        </div>
        <div class="input-group">
            <label>Target HYROX Finishing Time (minutes:seconds):</label>
            <input type="text" id="targetTime" placeholder="1:30:00">
        </div>
        <button onclick="generatePlan()">Generate Base Plan</button>
        <!-- Plan Display -->
        <div id="planOutput" class="plan-output"></div>
        <!-- Plan Modifications -->
        <h3>Adjust Your Plan</h3>
        <div class="input-group">
            <label>Equipment Limitations:</label>
            <input type="text" id="equipment" placeholder="e.g., no sleds">
        </div>
        <div class="input-group">
            <label>Session Changes:</label>
            <textarea id="changes" placeholder="e.g., can't do AM/PM sessions"></textarea>
        </div>
        <button onclick="updatePlan()">Update Plan</button>
    </div>
    <script>
        // Show/hide competition date based on purpose selection
        document.getElementById('trainingPurpose').addEventListener('change', function() {
            const dateGroup = document.getElementById('competitionDateGroup');
            dateGroup.style.display = this.value === 'competition' ? 'block' : 'none';
        });
        // Update category details
        function updateCategoryDetails(category) {
            const categoryDetails = document.getElementById('categoryDetails');
            categoryDetails.innerHTML = '';
            if (category === 'pro' || category === 'open') {
                categoryDetails.innerHTML = `
                    <p><b>Weight Categories (Men):</b></p>
                    <ul>
                        <li>Lightweight: < 75 kg</li>
                        <li>Middleweight: 75 - 85 kg</li>
                        <li>Heavyweight: 85 - 95 kg</li>
                        <li>Super Heavyweight: > 95 kg</li>
                    </ul>
                    <p><b>Weight Categories (Women):</b></p>
                    <ul>
                        <li>Lightweight: < 60 kg</li>
                        <li>Middleweight: 60 - 70 kg</li>
                        <li>Heavyweight: 70 - 80 kg</li>
                        <li>Super Heavyweight: > 80 kg</li>
                    </ul>
                    <p><b>Requirements:</b></p>
                    <ul>
                        <li>Must complete all 8 HYROX stations.</li>
                        <li>No time limits for individual stations.</li>
                        <li>Overall time determines ranking.</li>
                    </ul>
                `;
            } else if (category === 'proDoubles' || category === 'openDoubles') {
                categoryDetails.innerHTML = `
                    <p><b>Weight Categories:</b></p>
                    <ul>
                        <li>Combined weight of both athletes.</li>
                    </ul>
                    <p><b>Requirements:</b></p>
                    <ul>
                        <li>Must complete all 8 HYROX stations.</li>
                        <li>No time limits for individual stations.</li>
                        <li>Overall time determines ranking.</li>
                    </ul>
                `;
            } else if (category === 'relay') {
                categoryDetails.innerHTML = `
                    <p><b>Requirements:</b></p>
                    <ul>
                        <li>Team of 4 athletes.</li>
                        <li>Each athlete completes 2 stations in a row.</li>
                        <li>Must complete all 8 HYROX stations.</li>
                        <li>No time limits for individual stations.</li>
                        <li>Overall time determines ranking.</li>
                    </ul>
                `;
            }
        }
        // Generate workout plan
        async function generatePlan() {
            const pace = document.getElementById('currentPace').value;
            const sessions = document.getElementById('availability').value;
            const age = document.getElementById('userAge').value;
            const gender = document.getElementById('userGender').value;
            const weight = document.getElementById('userWeight').value;
            const height = document.getElementById('userHeight').value;
            const category = document.getElementById('hyroxCategory').value;
            const targetTime = document.getElementById('targetTime').value;
            try {
                const response = await fetch('/generate-plan', {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json'
                    },
                    body: JSON.stringify({ pace, sessions, age, gender, weight, height, category, targetTime })
                });
                const data = await response.json();
                if (data.error) {
                    alert(data.details);
                    return;
                }
                const planOutput = document.getElementById('planOutput');
                planOutput.innerHTML = '';
                data.plan.forEach(workout => {
                    const workoutElement = document.createElement('div');
                    workoutElement.innerHTML = `
                        <h3>${workout.day}</h3>
                        <p>${workout.workout}</p>
                    `;
                    planOutput.appendChild(workoutElement);
                });
            } catch (error) {
                console.error('Error fetching plan:', error);
                alert('Error generating plan. Please try again later.');
            }
        }
        // Update workout plan
        async function updatePlan() {
            const equipment = document.getElementById('equipment').value;
            const changes = document.getElementById('changes').value;
            // Add your logic to update the plan based on equipment and changes
            // For example, you could send a request to your backend with the equipment and changes,
            // and then update the planOutput div with the new plan.
        }
        // Add event listener to the category select element
        document.getElementById('hyroxCategory').addEventListener('change', function() {
            const category = this.value;
            updateCategoryDetails(category);
        });
    </script>
</body>
</html>
