# Egg
def calculate_area(base, height):
  """Calculates the area of a triangle.

  Args:
    base: The length of the base of the triangle.
    height: The height of the triangle.

  Returns:
    The area of the triangle.
  """
  area = (base * height) / 2
  return area

base = float(input("Enter the base of the triangle: "))
height = float(input("Enter the height of the triangle: "))

triangle_area = calculate_area(base, height)

print("The area of the triangle is:", triangle_area)
