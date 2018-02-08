Pay bill package will cover the followings:

1. Maintaining database of all the employees.
2. Generating pay and allowances bill for every month for the employees.
3. Generating arrear pay and allowances bill.
4. Generating pay slip and able to send it via eletronic form preferably e-mail.
5. View cummulative report - year wise, employee wise, pbr wise, bill no wise, financial year wise, quarter wise, month wise, 
6. Generating Quarterly incometax report in excel/csv for upload.
7. Generating Honourarium, Cash Award, Child Education Allowance, Ltc Leave Encashment Bill.
8. Generating Form -16 in bulk as well as individualy for a financial year or a period.
9. Generating Last Pay Certificate, Pay Certificate for a particular employee.

Details:

1. Maintaining database of all the employees:

  Master Table containg:
    
    i) Name
    ii) Date of Joining
    iii) Date of Birth
    iv) Date of superannuation
    v) Employee Office ID
    vi) Aadhar Number
    vii) PAN 
    viii) Whether residing at government housing? Y/n
    ix) Whether in New Pension Scheme? Y/n
    x) Salary status? Running/Stopped
    xi) Official email id
    xii) Alternate email id
    xiii) Mobile Number
    xiv) Alternate Mobile Number
    xv) Active Bank Account Number
    xvi) Bank IFSC FK Bank Master table
    xvii) PF/ NPS number #
    
    
  
# if employee in New Pension Scheme and PF Number not found  then it assumed that PRAN/(PF) number not alloted to the employee concerned.
# if PAN number found then income tax must be calculated as per income tax guideline for not furnishing PAN

  Government Quarter Details:
    
    i) Emp Id FK Employee Details table
    ii) Type of Quarter
    iii) Address
    iv) Whether still residing? Y/n
    v) Rate of License Fee
   
  Bank Master
  
    i) Bank Name
    ii) Bank Address
    iii) IFSC
    iv) MICR
  
  
    
