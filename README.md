# Python
<br>def print_inverted_pyramid(height):<BR>
   <BR> for i in range(height, 0, -1):<BR>
     <BR>   # Print leading spaces<BR>
       <BR> print(" " * (height - i), end="")<BR>
        
        # Print stars
        print("*" * (2 * i - 1))

<BR># Example usage<BR>
<BR>height = 5 <BR>
<BR>print_inverted_pyramid(height)<BR>
