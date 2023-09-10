- 👋 Hi, I’m @Lethokuhle2
- 👀 I’m interested in developing software
- 🌱 I’m currently upskilling as I am on a graduate program...
- 💞️ I’m looking to collaborate on ideas 
- 📫 How to reach me ...

<!---
Lethokuhle2/Lethokuhle2 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using NUnit.Framework;

namespace TDD_Course
{
    [TestFixture]
    public class FibonacciTests

    {
        [Test]
        public void TestFibonacci()
        {
            Assert.AreEqual(0, GetFibonacci(0));
            Assert.AreEqual(1, GetFibonacci(1));

        }
        private int GetFibonacci(int index)
        {
            if (index == 0) return 0;
            return 1;
        }
    }
}
