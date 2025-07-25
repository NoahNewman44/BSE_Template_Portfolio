# Magic Mirror Project
This project is a smart mirror that shows my calendar, weather, news, and even music info all in one place. I also added an integration of google assistant, allowing me to use custom voice commands such as switching between pages, which was the trickiest part of the whole project. Now it’s super handy and makes checking my day way easier.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Noah N | Moreau Catholic High School | Computer Engineering | Incoming Sophmore

![Headstone](IMG_3387.jpeg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/2LTlhNodHtc?si=-czZWU8tEoXDfSN1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/3US5norbM2o?si=PqMy66vXGKCBMSYp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my first milestone, I set up my Raspberry Pi by connecting the SD card to my computer with an SD card reader to flash the necessary OS. Once I did that, I moved on to the wiring aspect, which was fairly easy, there was only a power cable for the Pi, a USB and HDMI cable for the monitor, and two additional USB ports for the keyboard and mouse. Although, one challenge I ran into was SSHing into the Pi through Visual Studio Code. The problem was with the virtual machine but I eventually found an alternative method that worked.

After figuring that out ,I installed the MagicMirror2 software on the Pi. At this point, the monitor now displays all the default modules, such as the clock, calendar, and weather.

For my next milestones, I’m planning to add even more modules such as a Spotify integration, and customizing existing ones, such as configuring the weather module to where I live. 


# Schematics 
![Headstone Image](Schematic.png)

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs.

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Raspberry Pi 4 Starter Kit | Brains of the project, used to run and execute the code. | 91.99$ | <a href="https://www.amazon.com/RasTech-Raspberry-Starter-Heatsink-Screwdriver/dp/B0C8LV6VNZ/ref=sr_1_4?crid=3506HY00MCGVM&dib=eyJ2IjoiMSJ9._zkM62vSQ8p7tNr88715LdMv_qHh72Je-tkF9PXEa3chDE53QT4aZu4AGAb4ihE61QY4ZD55nKF6Fp2Kfs8t7AbafM_JrlJFfHo9OB4eAVGqa0EB-7aoBQHPmhKHZ2MW8ny-Kd44bMVlVxPlTWVk5YHIN5P3uKVqrE5Dcal0rKkHny-O6Xyb5ux2AOU6OwVbkag_bqBX66RQNRrgBuz-0pS43mcx93IZTQA9R8NaJJypYU2HAycp-XicTFmyU60a01Nfm9iuyo6B9yA8ppN3OQQyJ-NQ9xyNPxfTLwkqtng.yAYpU6outhQcZmOZhN9Wb6yTw7A85CNUbXZguGInZNg&dib_tag=se&keywords=raspberry%2Bpi%2Bkit&qid=1718848547&s=electronics&sprefix=rasbperry%2Bpi%2Bkit%2Celectronics%2C83&sr=1-4&th=1"> Link </a> |
| Dell e2314h Monitor | Used to display the code. | 47.79$ | <a href="https://www.pcliquidations.com/p64773-dell-e2314hf-23-fhd?variant=85229&gad_source=1&gad_campaignid=649733014&gbraid=0AAAAAD_tUvdfrKg0msY5ZBajmJg2ZvVFY&gclid=CjwKCAjw1ozEBhAdEiwAn9qbzW5qbEnjreyRlCgAYd1zTX9p0xvop7TJ8eJH04CHFE1mMX6EjTzFcxoCbqsQAvD_BwE)"> Link </a> |
| Sd Card Adapted | Used to download code onto SD card from my laptop. | 7.99$ | <a href="https://www.amazon.com/dp/B081VHSB2V?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1"> Link </a> |
| Keyboard and Mouse | Used to put in inputs for pi instead of just touchscreen | 21.99$ | <a href="https://www.amazon.com/gp/product/B07XDWCLYF/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1"> Link </a> |
| Reflective Film | Used on the monitor to turn it into a reflective mirror-like surface. | 4/99$ | <a href="https://www.amazon.com/dp/B0998PYXSH?ref_=ppx_hzsearch_conn_dt_b_fed_asin_title_1"> Link </a> |
| Hdmi to DVI-D | Used to connect my raspberry pi to the monitor.| 5.68$ | <a href="https://www.amazon.com/DTECH-Female-Adapter-Bi-Directional-Converter/dp/B07MJDYH21/ref=sr_1_5?crid=3V9A8DCCTS3P0&dib=eyJ2IjoiMSJ9.VaMbzXVXmZIRq1rTwzIL672mK8lbpK8vf4u6hf3YLFxZc7jWfjMB-zBX04fK80-niwao6vSzw_5_QqS69uPFNA0mqVg7P4Kk7-X05jKbR8ma3UKvfJTqrm6Ynsi-oM8DtZaYYc-p4Xpw_3cwKFSe6laOytUkh0WtL5ba29PRgrnMiZcNfRSXJF5_beU1a9l1WmWHcOhmUDoIxxB6z1SU9EfpN_wiUpXNb-Xf0DiDzYc.3uJLI0VEXxcGFBYCpHmiZwm5ImklQVVYGPFK3GW0gaA&dib_tag=se&keywords=dvi+to+hdmi+adapter&qid=1752515951&sprefix=dvid+to+%2Caps%2C280&sr=8-5"> Link </a> |


# Resources Used
- [Github Modules](https://github.com/MagicMirrorOrg/MagicMirror/wiki/3rd-party-modules)
    - [Spotify Module](https://github.com/skuethe/MMM-Spotify)
    - [NHL Module](https://github.com/parnic/MMM-NHL)
    - [Remote Control](https://github.com/Jopyth/MMM-Remote-Control)

Also used resources such as ChatGPT and Claude for researching different ways of implementing ideas. Used Home Assistant for my google home setup aswell.
