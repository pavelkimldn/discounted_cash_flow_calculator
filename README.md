# Discounted Cash Flow (DCF) Calculator 
**Project Overview**

The purpose of this project is to create a Discounted Cash Flow (DCF) calculator with an interactive graphical interface. The tool allows users to calculate the DCF and Net Present Value (NPV) of an investment based on projected cash flows, discount rates, terminal value, and initial investment.

The DCF method is used to estimate the value of an investment by discounting its expected future cash flows. The methodology involves several steps. First, users input the expected cash flows for each period. Next, they determine the discount rate, which is used to discount future cash flows to their present value. The terminal value, representing the value of the investment at the end of the projection period, is also considered. Each future cash flow is discounted back to its present value, and these values are summed to calculate the total DCF. Finally, the initial investment is subtracted from the total DCF to obtain the NPV.

This project features an interactive GUI built using Tkinter for easy input and real-time updates. Graphical visualization is achieved with Matplotlib, which is used to plot future cash flows, present value of cash flows, cumulative DCF, and discounted terminal value. Annotations on the graph provide clear values for better understanding.

**Code Description**

*Main Components*

The main components of the code include functions for DCF calculation, plotting, and the graphical user interface (GUI). The DCF calculation functions compute the DCF and NPV based on the user inputs. The plotting function uses Matplotlib to visualize the cash flows and DCF values. The GUI, built with Tkinter, handles user inputs and displays results.

*Key Functions*

The calculate_dcf_and_npv function takes cash flows, discount rate, terminal value, and initial investment as inputs. It calculates the present value of each cash flow, the discounted terminal value, and the cumulative DCF. The NPV is computed by subtracting the initial investment from the total DCF.

The plot_dcf function generates a plot showing future cash flows, present values of cash flows, cumulative DCF, and the discounted terminal value. Annotations are added to the plot for clarity.

The on_calculate function handles the calculation and updates the result display. It retrieves user inputs, calls the calculation function, and updates the result label and plot.

The update_cash_flow_entries function updates the cash flow input fields based on the number of periods specified by the user.

![github](https://github.com/pavelkimldn/discounted_cash_flow_calculator/blob/main/Picture%201.png)
