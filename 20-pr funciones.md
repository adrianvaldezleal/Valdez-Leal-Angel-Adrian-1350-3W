print("Valdez Leal Angel Adrian-1350-3W")
print(" ")
def tri_recursion(k):
    if k > 0:
        result = k + tri_recursion(k - 2)
        print(result)
    else:
        result = 0
    return result

print("\n\nRecursion Example Results")
tri_recursion(6)

![image](https://github.com/user-attachments/assets/b03f8317-d59b-4872-8556-710e8461de3f)
![image](https://github.com/user-attachments/assets/4a2b2322-d6d1-40f2-a6b2-5d8ba37c323f)
