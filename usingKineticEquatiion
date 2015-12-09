# Name: 
usingKineticEquation ()
## Examples:
void draw (){
println (usingKineticEquation (20,30 'k'))
}
float usingKineticEquation (float x, float y, char value) {
  float answer;
  if (value == 'k') {
    answer = .5*x*sq(y);
    return answer;
  }
  if (value == 'm') {
    answer = 2*x/sq(y); 
    return answer;
  }
  if (value == 'v'){
    answer = sqrt(2*x/y);
    return answer;
  }
  println("Make a valid choice");
  return 0;
}

## Description:
Solves for the missing variable in the Kinetic equation. 

## Syntax:
usingKineticEquation (float a, float b, char value)

##Parameters: 
if value == 'k'
  a= 'm'
  b= 'v'
  
if value == 'm'
  a= 'k'
  b= 'v'
  
if value == 'v' 
  a= 'k'
  b= 'm'
  

##Returns:
float

##Other notes:
Derived from the equation : k=(1/2)*m*sq(v)
