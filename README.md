<!DOCTYPE html>

<html>

<head>

	<title>Meal Planning Website</title>

	<link rel="stylesheet" type="text/css" href="style.css">

</head>

<body>

	<header>

		<h1>Meal Planning Website</h1>

	</header>

	<nav>

		<ul>

			<li><a href="#">Home</a></li>

			<li><a href="#">About Us</a></li>

			<li><a href="#">Contact Us</a></li>

		</ul>

	</nav>

	<main>

		<section>

			<h2>Get Started</h2>

			<form>

				<label for="age">Age:</label>

				<input type="text" id="age" name="age"><br>



				<label for="height">Height:</label>

				<input type="text" id="height" name="height"><br>



				<label for="weight">Weight:</label>

				<input type="text" id="weight" name="weight"><br>



				<label for="goal">Goal:</label>

				<select id="goal" name="goal">

					<option value="gain-muscle">Gain Muscle</option>

					<option value="lose-fat">Lose Fat</option>

					<option value="maintain">Maintain</option>

				</select><br>



				<button type="submit">Submit</button>

			</form>

		</section>



		<section>

			<h2>Meal Plan</h2>

			<p>Here is your personalized meal plan:</p>

			<ul>

				<li>Breakfast: Oatmeal with banana and almond milk</li>

				<li>Snack: Apple slices with peanut butter</li>

				<li>Lunch: Grilled chicken salad with mixed greens and vinaigrette dressing</li>

				<li>Snack: Greek yogurt with berries and honey</li>

				<li>Dinner: Baked salmon with quinoa and roasted vegetables</li>

			</ul>

			<p>Total cost for ingredients: $20</p>

		</section>

	</main>

	<footer>

		<p>&copy; 2023 Meal Planning Website</p>

	</footer>

</body>

</html>
