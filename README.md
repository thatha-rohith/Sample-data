# Sample-data

https://www.tableau.com/products/public/download

https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa3JVcXdwY1Joal9YOUhkWlJ2a0U3c1JFRms0Z3xBQ3Jtc0ttYUdyU0VEWXZnZEtYU0VjYXZKVXhYZUsybHdWSlpsVEliR3J6VDQxaDg2STZzUzhkVWdUOXFHZDFMZmtiR051Ujg1djRuWjEyc3VKODhvZ3dHZEpQQ3g0Vm5PRE1rYXc0eFlSb0tYV0VUYmtLck5lbw&q=https%3A%2F%2Fchandoo.org%2Fwp%2Fwp-content%2Fuploads%2F2023%2F03%2Fsample-data-10mins.xlsx&v=tNLp_JVipoQ&html_redirect=1


// KPI - Profit

IF SUM([Profit]) < 0 THEN "Low Profit"
ELSEIF SUM([Profit]) < 5000 THEN "Medium Profit"
ELSE "High Profit"
END

// KPI - Sales

IF SUM([Actual Sales]) > SUM([Target Sales])
THEN "Target Achieved"
ELSE "Target Missed"
END
