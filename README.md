# hotel-prices-HackerRank

In this challenge, the task is to debug the existing code to successfully execute all provided test files.

The given code defines two classes HotelRoom and HotelApartment denoting respectively a standard hotel room and a hotel apartment. An instance of any of these classes has two parameters: bedrooms and bathrooms denoting respectively the number of bedrooms and the number of bathrooms in the room.

The prices of a standard hotel room and hotel apartment are given as:

Hotel Room:  + .
Hotel Apartment: The price of a standard room with the same number bedrooms and bathrooms plus .
For example, if a standard room costs , then an apartment with the same number of bedrooms and bathrooms costs .

In hotel's codebase, there is a piece of code reading the list of rooms booked for today and calculates the total profit for the hotel. However, sometimes calculated profits are lower than they should be.

Debug the existing HotelRoom and HotelApartment classes' implementations so that the existing code computing the total profit returns a correct profit.

Your function will be tested against several cases by the locked template code.

Input Format

The input is read by the provided locked code template.
In the first line, there is a single integer  denoting the number of rooms booked for today.
After that  lines follow. Each of these lines begins with a room_type which is either standard or apartment, and is followed by the number of bedrooms and the number of bathrooms in this room.

Constraints

There is at least  and at most  bedrooms in a room
There is at least  and at most  bathrooms in a room
Output Format

The output is produced by the provided and locked code template. It calculates the total profit by iterating through the vector of all rooms read from the inpu
