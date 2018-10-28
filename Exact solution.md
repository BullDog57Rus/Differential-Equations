# Exact analitical solution

$$y' = \sin^2 x + y \cot x$$
Solve the complementary equation:
$$y'_1 - y_1 \cot x = 0$$
$$\frac{\mathrm{d}y_1}{\mathrm{d}x} = y_1 \cot x$$
$$\int \frac{\mathrm{d}y_1}{y_1} = \int \cot x \mathrm{d}x$$
$$\ln y_1 = \ln \sin x$$
$$y_1 = \sin x$$
Make a substitution:
$$y = y_1*u$$
Then:
$$\frac{\mathrm{d}u}{\mathrm{d}x} = \frac{\sin^2 x}{\sin x}$$
$$\int \mathrm{d}u = \int \sin x \mathrm{d}x$$
$$u = - \cos x + C$$
$$y = - \cos x \sin x + C \sin x$$
Solve Initial Value Problem for:
$$x_0 = 1, y_0 = 1$$
$$y_0 = - \cos x_0 \sin x_0 + C \sin x_0$$
$$1 = 0 + C$$
$$C = 1$$
The solution for IVP is:
$$y = - \cos x \sin x + \sin x$$