def euclidean_gcd(numbers):
	numbers.sort()
	numbers.reverse()
	n1 = numbers[0]

	for number in range(1, len(numbers)):
		n2 = numbers[number]
		r = n1 % n2

		if r == 1:
			n2 = 1
			break

		while r != 0:
			n1 = n2
			n2 = r
			r = n1 % n2

		n1 = n2

	print(n2, '\n')

#.#.#.

while True:
	numbers = input("Numbers: ")

	# Convert Strings to Ints
	numbers = numbers.split(" ")
	numbers = list(map(int, numbers))

	euclidean_gcd(numbers)
