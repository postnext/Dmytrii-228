class TestMathOperations(unittest.TestCase):
    def test_add(self):
        self.assertEqual(add(3, 5), 8)
        self.assertEqual(add(-1, 1), 0)

    def test_subtract(self):
        self.assertEqual(subtract(10, 4), 6)
        self.assertEqual(subtract(0, 7), -7)

    def test_multiply(self):
        self.assertEqual(multiply(3, 4), 12)
        self.assertEqual(multiply(-2, 5), -10)

    def test_divide(self):
        self.assertEqual(divide(10, 2), 5)
        with self.assertRaises(ValueError):
            divide(5, 0)

    def test_is_prime(self):
        self.assertTrue(is_prime(7))
        self.assertFalse(is_prime(8))
        self.assertTrue(is_prime(13))
        self.assertFalse(is_prime(1))

if __name__ == "__main__":
    unittest.main()

- 👋 Hi, I’m @Dmytrii-228
- 👀 I’m interested in crypto
- 🌱 I’m currently learning front end develop
- 💞️ I’m looking to collaborate on Mate academy
- 📫 How to reach me send me sms
- 😄 Pronouns: ...
- ⚡ Fun fact: just chill boy

<!---
Dmytrii-228/Dmytrii-228 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
