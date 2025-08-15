is → Identity Operator

Checks whether two variables point to the exact same object in memory.

It does not check for equality of values.

a = [1, 2, 3]
b = a
c = [1, 2, 3]

print(a is b)  # ✅ True — same object in memory
print(a is c)  # ❌ False — same values but different objects


2️⃣ in → Membership Operator

Checks whether an element exists inside a sequence, set, or dictionary.

fruits = ["apple", "banana", "cherry"]

print("banana" in fruits)  # ✅ True — found in list
print("grape" in fruits)   # ❌ False — not found


💡 Quick Summary Table:

Operator	Purpose	Example Result
is	Same object in memory?	a is b → True
in	Element exists in a container?	"x" in list → True
