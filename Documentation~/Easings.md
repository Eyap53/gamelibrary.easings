# Easings - Documentation

This package should be really easy and straightforward to use.
You only need to import the Easings namespace with :

    using Easings;

Then you can use any easing function directly in your C# script :

    Easing.QuadraticEaseInOut(0.73f);

You can also use the Interpolate function, which is equivalent :

    Easing.Interpolate(0.73f, Easing.Ease.QuadraticEaseInOut);

That's all !
