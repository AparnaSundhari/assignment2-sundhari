# assignment2-sundhari
second assignment 

# Aparna Sundhari

###### My Favorite place is Hyderabad

A major landmark of Hyderabad with four graceful **minarets** located in the old city. It was built by **Muhammed Quli Qutb Shah** as a memorial for plague victims. Charminar, on most occasions, is used to represent the city and the state and is hailed as a unique **Deccan** monument. It is in the midst of Charkaman which are four archways to roads leading in all four directions from the Charminar monument.Hyderbad is my birthplace, And I have many memories connected with hyderabad.

---

# Directions from Maryville to Hyderabad.
  1. Need to travel to Kansas-city Airport by car.
  2. Then Catch flights below:
     1. Kansas to Dallas Airpot.
     2. Dallas to Hyderabad Airpot.
  3. After coming outside of airport catch the below buses:
     1. Airport to LB Nagar.
     2. LB Nagar to Karmanghat.
  4. Walk for 5 Min to reach home.

* Items to be purchased:
  * Groceries:
    * Chips.
    * ice-cream.
    * buscuits.
  * Drinks:
    * Thumbsup.
    * Maaza.
  * Baloons.
  * Bluetooth Speaker.

**[AboutMe.md](AboutMe.md)**

---

# Food/Drinks i recommand:

The below Food/Drinks you must try if you visit Hyderbad:

| Food/Drink | Location | Expected Price |
| --- | --- | --- |
| Mutton Biryani | Shah Gouse | 500 |
| Fried Maggie | DLF | 50 |
| Dosa | Ram Ki Bandi | 100 |
| Pani Puri | Gokul Chat | 75 |

---

# Pithy Quotes

> "Don't cry because it's over. Smile because it happened." —*Dr. Seuss*</br>
> "Anyone who has never made a mistake has never tried anything new." —*Albert Einstein*

---

# Area of simple polygon 

> The shoelace formula or shoelace algorithm (also known as Gauss's area formula and the surveyor's formula) is a mathematical algorithm to determine the area of a simple polygon whose vertices are described by their Cartesian coordinates in the plane.

[Click here to know more](https://en.wikipedia.org/wiki/Shoelace_formula)

```
double area(const vector<point>& fig) {
    double res = 0;
    for (unsigned i = 0; i < fig.size(); i++) {
        point p = i ? fig[i - 1] : fig.back();
        point q = fig[i];
        res += (p.x - q.x) * (p.y + q.y);
    }
    return fabs(res) / 2;
}
```

[Code Source](https://cp-algorithms.com/geometry/area-of-simple-polygon.html)