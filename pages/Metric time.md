title: Metric time
id: metrictime
main_file: Metric time.py
status: personal hobby horse, broken
type: addon
status_color: red
status_text_color: white
abstract: Shows times in some spots as days or years.
first_image: Studied in days.png
first_alt: The time studied is shown in days, not hours.

This add-on is just me riding my favorite hobby horse,
[metric time](http://en.wikipedia.org/wiki/Decimal_time#Fractional
days).
I think splitting days into hours, minutes and seconds is about as
silly as splitting lengths into inches, feet, yards, rods, chains and
miles or using pounds and ounces and stones and who-knows-what else for
mass. (Or weight. Better not go
[there](http://en.wikipedia.org/wiki/Slug (mass))! And how much is a
[gallon](http://en.wikipedia.org/wiki/Gallon)‽)

<blockquote class="nb">
This add-on assumes that a complete Python is installed. It will not
work with just Anki installed. Specifically, it uses the decimal
module, which is part of the Python standard library, but not included
with Anki.
</blockquote>


This add-on replaces the standard time-formating function with one
that returns times shorter than a year as days – even times much
shorter than a day. Longer times are written as years with one decimal
place.