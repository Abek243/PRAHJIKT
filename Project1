## Assignment: Project One, Question 3, pg. 14 Part A
## Author: Gavin Rostar
## Version: 05.08.2012.01
## Purpose: Assigns prices of homes

use 5.14.1;
use warnings;

my ($lotNum,$bedNum,$bathNum, $garageSize, $price);

sub main{
          setlotNum();
          setbedNum();
          setbathNum();
          setgarageSize();
          determinelotNum();
          printResults();
}

main();

sub setlotNum {
     print "\n\nWhat lot number do you want?";
     chomp ($lotNum = <STDIN>);
}

sub setbedNum {
          print "How many bedrooms would you like?";
          chomp ($bedNum = <STDIN>);
}
sub setbathNum {
     print "How many bathrooms would you like?";
     chomp ($bathNum = <STDIN>);
}

sub setgarageSize {
          print "How many vehicles do you want in your garage?";
          chomp ($garageSize = <STDIN>);
}

sub determinelotNum {
          use constant BASEPRICE => 50000;
          use constant BEDPRICE => 17000;
          use constant BATHPRICE => 12000;
          use constant GARAGEPRICE => 6000;
          $price = BASEPRICE + BEDPRICE * $bedNum + BATHPRICE * $bathNum  + GARAGEPRICE * $garageSize;
          
}

sub printResults {
          system("cls");
          print "\n\nYour total is $price ";
          
}
