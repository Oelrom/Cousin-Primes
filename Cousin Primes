int num, numPlus4;
for (int i = 2; i < 100; i++)
{
	bool result = true;
	for (int a = 2; a <= Math.Sqrt(i) && result == true; a++)
	{
		if (i % a == 0)
		result = false;
	}
	if (result == true)
	{
		num = i;
		numPlus4 = num + 4;
		result = true;
		for (int a = 2; a <= Math.Sqrt(numPlus4) && result == true; a++)
		{
			if (numPlus4 % a == 0)
			result = false;
		}
	if (result == true)
	Console.WriteLine(num + " - " + numPlus4);
}
