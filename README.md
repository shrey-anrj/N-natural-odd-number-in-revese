#include <stdio.h>

void main ()
{
  int i, n;
  printf ("Enter no of natural no to be displayed:\t");
  scanf ("%d", &n);
  for (i = n; i >= 0 ; i--)
    {
      if (i % 2 != 0)
	printf ("\n%d", i);
    }
}
