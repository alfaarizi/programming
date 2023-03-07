            //                  Program 1:
            /*
            Console.Write("Enter the length of the rectangle: ");
            int length = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter the width of the rectangle: ");
            int width = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("The area of the rectangle is (l x w) = " + length*width);
            Console.WriteLine("The perimeter of rectangle is 2(l + w) = " + 2*(length+width));
            */

            //                  Program 2:
            /*
            Console.Write("Enter a = ");
            int a = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter b = ");
            int b = Convert.ToInt32(Console.ReadLine());

            int expansion = (a + b)*(a + b);

            Console.WriteLine("= ({0} + {1})^2", a, b);
            Console.WriteLine("= {0}^2 + 2*{0}*{1} + {1}^2", a, b);
            Console.WriteLine("= {0} + {1} + {2}", a*a, 2*a*b, b*b);
            Console.WriteLine("= " + expansion);
            */

            //                  Program 3:
            /*
            Console.Write("Enter Length for Side 1: ");
            int side1 = Convert.ToInt32(Console.ReadLine());
            
            Console.Write("Enter Length for Side 2: ");
            int side2 = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter Length for Side 3: ");
            int side3 = Convert.ToInt32(Console.ReadLine());

            bool case1 = Math.Pow(side1, 2) == Math.Pow(side2, 2) + Math.Pow(side3, 2);
            bool case2 = Math.Pow(side2, 2) == Math.Pow(side1, 2) + Math.Pow(side3, 2);
            bool case3 = Math.Pow(side3, 2) == Math.Pow(side1, 2) + Math.Pow(side2, 2);

            if (case1 || case2 || case3) {
                Console.WriteLine("The given triangle is a right angled triangle.");
            } else {
                Console.WriteLine("The given triangle is not right angled triangle.");
            }
            */

            //                  Program 4:
            /*
            Console.Write("Amount of petrol consumed (liters): ");
            float l = float.Parse(Console.ReadLine());

            Console.Write("Length of the trip (km): ");
            float km = float.Parse(Console.ReadLine());

            float consumption = l / km * 100;

            Console.WriteLine("The consumption of the car is {0} (liters / 100km)", consumption);
            */

            //                  Program 5:
            /*
            Console.Write("Number of kids: ");
            float kid = float.Parse(Console.ReadLine());

            Console.Write("Number of apples: ");
            float apple = float.Parse(Console.ReadLine());

            float remainingApple = apple % kid;
            int sharedApple = Convert.ToInt32(apple / kid);

            if (apple > kid) {
                Console.WriteLine("Every kid gets {0} apples and there are {1} apples left.", sharedApple, remainingApple);
            } return;
            */

            //                  Program 6:
            /*
            Console.Write("Enter two integers: ");
            string[] num = Console.ReadLine().Split(' ');

            int num1 = Convert.ToInt32(num[0]);
            int num2 = Convert.ToInt32(num[1]);
            int smallNum;
            
            while (num1 != num2)
            {
                if (num1 < num2) {
                    smallNum = num1;
                }
                else {
                    smallNum = num2;
                }
                Console.WriteLine("The smaller number is {0}.", smallNum);
                return;
            }
            return;
            */

            //                  Program 7:
            /*
            Console.Write("N: ");
            int num = Console.ReadLine().Length;

            bool is3Digit = num == 3;
    
                if (is3Digit) {
                    Console.WriteLine("{0} is a 3-digit number", num);
                }
                else {
                    Console.WriteLine("{0} is not a 3-digit number", num);
                }
            */

            //                  Program 8:
            /*
            Console.Write("Enter two numbers: ");
            String[] num = Console.ReadLine().Split(' ');

            bool isOddNum1 = Convert.ToInt32(num[0]) % 2 == 1;
            bool isOddNum2 = Convert.ToInt32(num[1]) % 2 == 1;


            if (isOddNum1 || isOddNum2) {
                Console.WriteLine("Yes, there is an odd one.");
            }
            else {
                Console.WriteLine("None of them is odd.");
            } return;
            */

            //                  Program 9:
            /*
            Console.Write("Enter three words: ");
            String[] word = (Console.ReadLine().Split(' '));

            int num1 = (word[0]).Length;
            int num2 = (word[1]).Length;
            int num3 = (word[2]).Length;

            int max = Math.Max(num1, Math.Max(num2, num3));

            if (num1 == max) {
                Console.WriteLine("The longest word is " + word[0]);
            } else if (num2 == max) {
                Console.WriteLine("The longest word is " + word[1]);
            } else {
                Console.WriteLine("The longest word is " + word[2]);
            }
            */

            //                  Program 10:
            /*
            Console.WriteLine("In the equation a*x^2 + b*x + c = 0");
            
            Console.Write("The value of a: ");
            double a = Convert.ToDouble(Console.ReadLine());

            Console.Write("The value of b: ");
            double b = Convert.ToDouble(Console.ReadLine());

            Console.Write("The value of c: ");
            double c = Convert.ToDouble(Console.ReadLine());

            double discriminant = b * b - 4 * a * c;

            double x1 = (-1 * b + (Math.Sqrt(b * b - 4 * a * c))) / (2 * a);
            double x2 = (-1 * b - (Math.Sqrt(b * b - 4 * a * c))) / (2 * a);
            
            if (discriminant > 0) {
                Console.WriteLine("The equation has 2 solutions, x1 = {0}, x2 = {1}", x1, x2);
            } else if (discriminant == 0) {
                Console.WriteLine("The equation has a solution, x = {0}", x1);
            } else {
                Console.WriteLine("No solutions, x are not real numbers");
            } 
            return;
            */
