 ## **Transforming EDA Projects to Dashboards**
 - [Dashboard](https://drive.google.com/file/d/1X9co1SI0P8S44_yV_8pQPxXMVpfJvRg9/view?usp=drive_link)

**Create PowerBI Dashboard from the same dataset on which EDA was performed i,e Hotel Bookings Analysis capstone project.**

### Problem Statement:

**"Develop a Power BI dashboard to visualize and analyze hotel booking data, enabling stakeholders to gain actionable insights into booking trends, customer behavior, and key performance metrics. The dashboard will be created using cleaned and transformed data, focusing on improving decision-making processes related to occupancy rates, revenue management, customer segmentation, and marketing strategies."**

### Key Aspects to Address:
1. **Data Overview:** Provide a comprehensive view of the cleaned and transformed hotel booking data, including metrics such as booking dates, customer demographics, and booking sources.
  
2. **Occupancy and Revenue Analysis:** Visualize occupancy rates, average daily rate (ADR), and revenue per available room (RevPAR) to identify trends and optimize pricing strategies.

3. **Customer Segmentation:** Segment customers based on demographics, booking behavior, and preferences to tailor marketing efforts and improve customer satisfaction.

4. **Booking Patterns:** Analyze booking patterns by season, day of the week, lead time, and cancellation rates to forecast demand and manage resources effectively.

5. **Comparative Analysis:** Compare performance across different hotels, room types, or geographical locations to identify strengths and areas for improvement.

6. **Performance Metrics:** Monitor key performance indicators (KPIs) in real-time to assess the effectiveness of current strategies and make data-driven decisions.
**Dataset Selection:**

**Dataset Details:**

- **Dataset Name:** new_hotel_bookings

- **Dataser Variables**:

hotel: Name of hotel ( City or Resort).

is_canceled: Whether the booking is canceled or not (0 for
no canceled and 1 for canceled).

lead_time: time (in days) between booking transaction and * actual arrival.

arrival_date_year: Year of arrival

arrival_date_month: month of arrival.

arrival_date_week_number: week number of arrival date.

arrival_date_day_of_month: Day of month of arrival date.

stays_in_weekend_nights: No. of weekend nights spent in a hotel.

stays_in_week_nights: No. of weeknights spent in a hotel.

adults: No. of adults in single booking record.

children: No. of children in single booking record.

babies: No. of babies in single booking record.

meal: Type of meal chosen.

country: Country of origin of customers (as mentioned by them).

market_segment: What segment via booking was made and for what purpose.

distribution_channel: Via which medium booking was made.

is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for Yes).

previous_cancellations: No. of previous canceled bookings.

previous_bookings_not_canceled: No. of previous non-canceled bookings.

reserved_room_type: Room type reserved by a customer.

assigned_room_type: Room type assigned to the customer.

booking_changes: No. of booking changes done by customers.

deposit_type: Type of deposit at the time of making a
booking (No deposit/ Refundable/ No refund).

agent: Id of agent for booking.

company: Id of the company making a booking.

days_in_waiting_list: No. of days on waiting list.

customer_type: Type of customer(Transient, Group, etc.)

adr: Average Daily rate.( Average daily rate measures the average revenue earned per occupied room per day)

required_car_parking_spaces: No. of car parking asked in booking.

total_of_special_requests: total no. of special request.

reservation_status: Whether a customer has checked out or canceled,or not showed.

reservation_status_date: Date of making reservation status.

total_stay: total no of days to stay

total_people: total no of people including children, adult &babies.


**How to proceed with the PowerBi dashboard:**

1. **Data Cleaning**

Begin by addressing the disorder and inconsistency within the dataset. Utilise Jupyter Notebook and Public/PowerBI Prep to systematically cleanse the data, rectifying discrepancies, eliminating duplicates, and standardising formats.

1. **Data Transformation**

Generate supplementary columns by utilising pre-existing categorical data. These columns will be derived from extensive descriptive text, which, in its original form, proved arduous to comprehend and unsuitable for visualisation purposes. The extra columns that we created gave a much clear sense of how to approach and make an effective visualisation.

1. **Public/PowerBI**

Employ Public/PowerBi desktop to create charts and dashboard which gives/shows important insights in the data.
