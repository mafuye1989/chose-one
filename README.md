<!DOCTYPE html>
<html>
<head>
    <title>Survey Options</title>
    <script>
        function redirectToSurvey(language) {
            if (language === 'amharic') {
                window.location.href = 'https://docs.google.com/forms/d/e/1FAIpQLScgXjU_CMyxnQuL5tbhUvfzN3SAm-hWAtSVZWOLT2WR5fIvJg/viewform?usp=sf_link';
            } else if (language === 'english') {
                window.location.href = 'https://docs.google.com/forms/d/e/1FAIpQLScMfP09AbvoE33gfePzC1Uu99gaEFioMzpZH2q1cGOlxH20MQ/viewform?usp=sf_link';
            }
        }
    </script>
</head>
<body>
    <h1>Survey Options</h1>
    <button onclick="redirectToSurvey('amharic')">Amharic Survey</button>
    <button onclick="redirectToSurvey('english')">English Survey</button>
</body>
</html>
