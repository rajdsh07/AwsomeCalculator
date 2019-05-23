# AwsomeCalculator
LAB #2

   public void GetAddition_Input3point4and5point6_Returns9point0()
        {

            //Arrange
            double number1 = 3.4;
            double number2 = 5.6;

            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetAddition_Input20point1and25point9_Returns46point0()
        {
            // Arrange
            double number1 = 20.1;
            double number2 = 25.9;
            double expectedResult = number1 + number2;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetAddition_Input33point0and55point0_Returns88point0()
        {
            // Arrange
            double number1 = 33;
            double number2 = 55;
            double expectedResult = number1 + number2;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }



Subtraction --> Code
[Test]
        public void GetSubtraction_Input2point0and1point0_Returns1point0()
        {
            // Arrange
            double number1 = 2.0;
            double number2 = 1.0;
            double expectedResult = number1 - number2;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        
        
        Multiuplication --> ^%&$%^$%^$
        
        
        
