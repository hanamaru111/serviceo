<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>하나마루 세차장 예약</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/flatpickr/dist/flatpickr.min.css">
</head>
<body>
    <div class="container">
        <h1>하나마루 세차장 예약</h1>
        <div class="booking-form">
            <div class="form-group">
                <label for="date">예약 날짜</label>
                <input type="text" id="date" class="date-picker" placeholder="날짜를 선택하세요">
            </div>
            <div class="form-group">
                <label for="carNumber">차량 번호</label>
                <input type="text" id="carNumber" placeholder="차량 번호를 입력하세요">
            </div>
            <div class="form-group">
                <label for="service">서비스 선택</label>
                <select id="service">
                    <option value="interior">내부 세차</option>
                </select>
            </div>
            <button id="submitBtn" class="submit-btn">예약하기</button>
        </div>
        <div id="bookingStatus" class="booking-status"></div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/flatpickr"></script>
    <script src="https://cdn.jsdelivr.net/npm/flatpickr/dist/l10n/ko.js"></script>
    <script src="script.js"></script>
</body>
</html> 
