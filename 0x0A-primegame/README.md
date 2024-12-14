#Prime Game Problem
    Topic: Eratosthenes algori
    Determines the winner in the prime game using
    Eratosthenes prime sieving algorithm
    """
    Ben = 0
    Maria = 0

    for round in range(x):
        playing_numbers = [num for num in range(2, nums[round] + 1)]
        index = 0
        # Sieve prime numbers per round
        # Determine winner - if number of primes is even player 1 wins
        # else player 2 wins. Player 2  also wins if there is only one
        # number to pick from
       
