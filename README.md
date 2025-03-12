# ISSClassActivity
There are several changes which I performed in order to make the file running

Firstly there were many places where : were missing such as
def is_narc 
for num in range(start, end + 1)
if is_narc(num)

now,
sum_of_powers = sum(int(digit) ** num_digits for digit in num_str)
One more * was here , *** were there but for exponenent ** are needed

another one,
   num_str = str(n)
    num_digits = len(num_str)

    here == were use instead of = which was wrong


one more,

    """Print all narc numbers in a given range."""
    for num in range(start, end + 1):
        if is_narc(num):
            print(num)
    //WHOLE OF THIS PARA WAS WRITTEN IN WRONG INDENTATION WITH RESPECT TO def print_narcis_numbers(start, end):

one more,

FUNTION NAMES WERE CALLED WRONGLY

def print_narcis_numbers(start, end):  // start end was written instead of start,end which is wrong