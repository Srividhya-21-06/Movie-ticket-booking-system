movies = {'1': 'Avengers: Endgame', '2': 'The Lion King', '3': 'Joker', '4': 'Avatar','5': 'Godzilla'}
tickets = {'1': 100, '2': 80, '3': 120, '4': 200,'5': 180}
print("Welcome to the Movie Ticket Booking System!")
print("Select a movie:")
for key, value in movies.items():
    print(f"{key}: {value}")

movie_choice = input("Enter the movie number: ")
if movie_choice in movies:
    num_tickets = int(input("Enter the number of tickets: "))
