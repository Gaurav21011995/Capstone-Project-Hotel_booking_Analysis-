This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies,and the number of available parking spaces, among other things. Using the booking information about these hotels, the challenge is to build a model to predict booking cancellation based on the following fields:

Data Description:

hotel (str) - Hotel (H1 = Resort Hotel or H2 = City Hotel)

lead_time (int) - Number of days that elapsed between the entering date of the booking into the PMS and the arrival date

arrival_date_year (int) - Year of arrival date

arrival_date_month (str) - Month of arrival date

arrival_date_week_number (int) - Week number of year for arrival date

arrival_date_day_of_month (int) - Day of arrival date

stays_in_weekend_nights (int) - Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel

stays_in_week_nights (int) - Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel

adults (int) - Number of adults

children (float) - Number of children

babies (int) - Number of babies

meal (str) - Type of meal booked. Categories are presented in standard hospitality meal packages: (Undefined/SC = no meal package, BB = Bed & Breakfast, HB = Half board – breakfast and one other meal - usually dinner, FB = Full board – breakfast, lunch and dinner)

country (str) - Country of origin. Categories are represented in the ISO 3155–3:2013 format

market_segment (str) - Market segment designation (TA = Travel Agents, TO = Tour Operators)

distribution_channel (str) - Booking distribution channel (TA = Travel Agents, TO = Tour Operators)

is_repeated_guest (int) - Value indicating if the booking name was from a repeated guest (1) or not (0)

previous_cancellations (int) - Number of previous bookings that were cancelled by the customer prior to the current booking

previous_bookings_not_canceled (int) - Number of previous bookings not cancelled by the customer prior to the current booking

reserved_room_type (str) - Code of room type reserved. Code is presented instead of designation for anonymity reasons

assigned_room_type (str) - Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons

booking_changes (int) - Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation

deposit_type (str) - Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: (No Deposit = no deposit was made, Non Refund = a deposit was made in the value of the total stay cost, Refundable = a deposit was made with a value under the total cost of stay)

agent (float) - ID of the travel agency that made the booking

company (float) - ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons
days_in_waiting_list (int) - Number of days the booking was in the waiting list before it was confirmed to the customer

customer_type (str) - Type of booking, assuming one of four categories: (Contract = when the booking has an allotment or other type of contract associated to it, Group = when the booking is associated to a group, Transient = when the booking is not part of a group or contract, and is not associated to other transient booking, Transient-party = when the booking is transient, but is associated to at least other transient booking

adr (float) - Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights

required_car_parking_spaces (int) - Number of car parking spaces required by the customer

total_of_special_requests (int) - Number of special requests made by the customer (e.g. twin bed or high floor)

reservation_status (str) - Reservation last status, assuming one of three categories: (Canceled = booking was canceled by the customer, Check-Out = customer has checked in but already departed, No-Show = customer did not check-in and did inform the hotel of the reason why)

reservation_status_date (str) - Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel
