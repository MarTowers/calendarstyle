# calendarstyle
* {
  box-sizing: border-box;
  font-family: Verdana, Geneva, Tahoma, sans-serif ;
  list-style: none;
  margin: 0;
  outline: none;
  padding: 1;
}

body, html {
  height: 100%;
}

body {
  background: #e5dde7;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}

.container {
  align-items: center;
  display: flex;
  height: 100%;
  justify-content: center;
  margin: 0 auto;
  max-width: 500px;
  width: 100%;
}

.calendar {
  background: #3d4549;
  border-radius: 4px;
  box-shadow: 0 5px 20px rgba(250, 243, 243, 0.3);
  height: 500px;
  perspective: 1000;
  width: 100%;
}

/* Front */

.current-date {
  border-bottom: 1px solid rgba(158, 195, 212, 0.6);
  display: flex;
  justify-content: space-between;
  padding: 30px 40px;
}

.current-date h1 {
  color: #dfebed;
  font-size: 1.4em;
  font-weight: 300;
}

.week-days {
  color: #dfebed;
  display: flex;
  justify-content: space-between;
  font-weight: 600;
  padding: 30px 40px;
}

.days {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.weeks {
  color: #fff;
  display: flex;
  flex-direction: column;
  padding: 0 40px;
}

.weeks div {
  display: flex;
  font-size: 1.2em;
  font-weight: 300;
  justify-content: space-between;
  margin-bottom: 20px;
  width: 100%;
}

.last-month {
  opacity: .1;
}

.weeks span {
  padding: 10px;
}

.weeks span:not(.last-month):hover {
  cursor: pointer;
  font-weight: 800;
}



