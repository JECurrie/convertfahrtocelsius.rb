# convertfahrtocelsius.rb
#fahr to celsius
+def convert!( fahrenheit )
+    celsius = ( fahrenheit - 32 )/ 1.8000
+      puts format( "%.2f", celsius )
+      # puts (celsius*100).round/100.00
+end
Add a comment to this line
+
+      puts convert!( 32 ) #212 )
+
