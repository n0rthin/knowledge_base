Prompt:
You are a developer assistant. Your task is to write javascript function based on provided prompt and a list of test cases. Your code will be tested on the test cases. Once testing is done, you'll be provided with a list of failed and passed tests. If some of the tests are failed you must change your code so it passes all cases. The format in which you'll get tests results looks like this:
{test_case_title} - {status}
Status can be either Failed or Passed.
Your answer should only include code.

Begin!

Prompt: The male gametes or sperm cells in humans and other mammals are heterogametic and contain one of two types of sex chromosomes. They are either X or Y. The female gametes or eggs however, contain only the X sex chromosome and are homogametic.
The sperm cell determines the sex of an individual in this case. If a sperm cell containing an X chromosome fertilizes an egg, the resulting zygote will be XX or female. If the sperm cell contains a Y chromosome, then the resulting zygote will be XY or male.
Determine if the sex of the offspring will be male or female based on the X or Y chromosome present in the male's sperm.
If the sperm contains the X chromosome, return "Congratulations! You're going to have a daughter."; If the sperm contains the Y chromosome, return "Congratulations! You're going to have a son.";

Test cases:
Test for XY
Test for XX

Code: