from tkinter import *
from tkinter import messagebox
from tkinter.messagebox import *


root = Tk()
root.title("LOAN CALCULATOR")
#icon
root.iconbitmap("")
root.geometry("1000x500+50+50")
root.config(bg="grey")
f = ("Century", 25 , "bold")


#title
title_label = Label(root, text="LOAN CALCULATOR", font=("Arial", 40, "bold"), bg="black", fg="white")
title_label.place(x=600, y=40)

#label and Entry fields
loan_amount_lab = Label(root, text="Loan Amount : ", font = f, fg= "red")
loan_amount_lab.place(x=100, y=120)
loan_amount_ent = Entry(root, font = f)
loan_amount_ent.place(x=550, y=120)

loan_tenure_lab = Label(root, text="Loan Tenure (months) : ", font = f)
loan_tenure_lab.place(x=100, y=180)
loan_tenure_ent = Entry(root, font = f)
loan_tenure_ent.place(x=550, y=180)

interest_rate_lab = Label(root, text="Interest Rate (%) : ", font = f)
interest_rate_lab.place(x=100, y=240)
interest_rate_ent = Entry(root, font = f)
interest_rate_ent.place(x=550, y=240)


#result labels
emi_amount_lab = Label(root, text="EMI Amount is ", font=f)
emi_amount_lab.place(x=100, y=400)

total_interest_lab = Label(root, text="Total Interest to pay is ", font=f)
total_interest_lab.place(x=100, y=450)

total_payment_lab = Label(root, text="Total Payment is ", font=f, fg="red")
total_payment_lab.place(x=100, y=500)


def calculate_loan():
	try:

		loan_amount = float(loan_amount_ent.get())
		loan_tenure = int(loan_tenure_ent.get())
		interest_rate = float(interest_rate_ent.get())

		if loan_amount_ent.get().strip() == "" or loan_tenure_ent.get().strip() == "" or interest_rate_ent.get().strip() == "":
			raise ValueError("No empty field is allowed")

		if loan_amount < 0:
			raise ValueError("Loan Amount should be greater than zero and should not be Negative(-ve)")
		if loan_tenure < 0:
			raise ValueError("Loan Tenure should be greater than zero and should not be Negative(-ve)")
		if interest_rate < 0:
			raise ValueError("Interest Rate should be greater than zero and should not be Negative(-ve)")

		
#loan calculation

		monthly_interest_rate = interest_rate / 100 / 12
		emi = loan_amount * monthly_interest_rate * ((1 + monthly_interest_rate) ** loan_tenure) / (((1 + monthly_interest_rate) ** loan_tenure) - 1)
		total_interest = emi * loan_tenure - loan_amount
		total_payment = emi * loan_tenure

#printing result
        
		emi_amount_lab.config(text=f"EMI Amount: {emi:.2f}")
		total_interest_lab.config(text=f"Total Interest Payable: {total_interest:.2f}")
		total_payment_lab.config(text=f"Total Payment: {total_payment:.2f}")

	except ValueError as ve:
		messagebox.showerror("Issue : ", str(ve))
	
	except Exception as e:
		messagebox.showerror("Issue : ", str(e))



#button to calculate
cal_btn = Button(root, text="Calculate", font=f, fg="red",command=calculate_loan)
cal_btn.place(x=550 , y=350)


#exit msg box
def on_closing():
	if askyesno("Quit","Do you want to exit???"):
		root.destroy()
root.protocol("WM_DELETE_WINDOW", on_closing)

root.mainloop()