
  curl -d 'id=48ff72065067555042462387' \
     -d 'access_token=a709268591bb27bd5f7b52cf10e5241a1c1266e7' \
       https://api.spark.io/v1/devices

   curl "https://api.spark.io/v1/devices/48ff72065067555042462387/temperature?access_token=a709268591bb27bd5f7b52cf10e5241a1c1266e7"

   curl https://api.spark.io/v1/devices/48ff72065067555042462387/brew \
     -d access_token=a709268591bb27bd5f7b52cf10e5241a1c1266e7 \
     -d "args=202,230"

     curl https://api.spark.io/v1/devices/48ff72065067555042462387/myloop \
     -d access_token=a709268591bb27bd5f7b52cf10e5241a1c1266e7 \
      -d "args=202,230"


    curl https://api.spark.io/v1/devices/48ff72065067555042462387/digitalwrite \
     -d access_token=a709268591bb27bd5f7b52cf10e5241a1c1266e7 \
      -d "args=D7,HIGH"

