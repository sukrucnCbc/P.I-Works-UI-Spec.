{
 "metadata": {
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.0"
  },
  "orig_nbformat": 2,
  "kernelspec": {
   "name": "python390jvsc74a57bd052c3714533e4dc4eb540c59ad44074480e567b128c722010b2a02abd39603343",
   "display_name": "Python 3.9.0 64-bit"
  },
  "metadata": {
   "interpreter": {
    "hash": "52c3714533e4dc4eb540c59ad44074480e567b128c722010b2a02abd39603343"
   }
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2,
 "cells": [
  {
   "source": [
    "# *User Interface Specification Document*"
   ],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "source": [
    "![Photo](https://raw.githubusercontent.com/sukrucnCbc/P.I-Works-UI-Spec./main/PI.png)\n",
    "\n",
    "## This user interface specification document has been prepared for the development of the user management screen seen above."
   ],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "source": [
    "# Section A "
   ],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "source": [
    "## Purpose\n",
    "It is the most basic area to be used to add new users to the system. \"New User\" and \"Save User\" buttons will perform these operations.\n",
    "\n",
    "## Navigation % User Interaction \n",
    "The New User button makes it possible to see the Section C area on the screen. After successful user addition, Save User Button allows the entered information to be printed on the table in Section B field. Only if the information is entered completely, it is possible to activate the save user button.\n",
    "At the time of adding a new user, if the Enabled button is not clicked, the user is marked as Disabled. The \"Hide Disabled User\" checkbox prevents these users from being seen in the table on the screen.\n",
    "\n",
    "### This part, like the navbar, should completely cover the top of the screen horizontally and include:\n",
    "+ New User Button: This button should be on the left side of Section A. The button color should be # 3daae0 and the text color should be white. Also, there should be a \"+\" icon outside of the text.\n",
    "+ Hide Disabled User (checkbox): There should be a \"Hide Disabled User\" label right next to the button and a checkbox.\n",
    "+ Save User Button: Unlike the previous ones, this button should be on the right. The button color should be # 3daae0 and the text color should be white.\n"
   ],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "source": [],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "source": [
    "## Section B"
   ],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "source": [
    "## Purpose\n",
    "It enables newly added users to be seen and listed in the table. In addition, filtering can be done between users.\n",
    "## Navigation & User Interaction\n",
    "The table in this section performs the process of listing and sorting newly added users to the system. Searching and reverse sorting can be done by clicking the sort and filter button next to each title.\n",
    "\n",
    "### It should cover 40% of the area of ​​the screen at the bottom, except for the upper navbar, and should be close to the left. This part includes:\n",
    "It should be a 4 column table with headings + ID, User Name, Email, Enabled.\n",
    "+ The color of the table headers should be #3daae0 and the text color should be white. There should be a \"Filter\" icon next to the labels of each title.\n",
    "+ Each table header should also work as a button and the order should change to ASC and DESC when these buttons are clicked.\n",
    "+ ID must be increased by one for each new element included in the list."
   ],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "source": [
    "## Section C"
   ],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "source": [
    "## Purpose\n",
    "It is the most basic area to be used to add new users to the system. After all information is entered completely, the user role is determined.\n",
    "\n",
    "## Navigation & User Interaction\n",
    "All textboxes should be filled in completely and the Enabled status should be checked. This makes it visible in the table while listing the user. Also, this section allows the user's role to be selected.\n",
    "\n",
    "\n",
    "### It should cover 40% of the area of ​​the screen at the bottom, except for the upper navbar, and it should be on the right. This part includes:\n",
    "+ Section It should contain \"New User\" title in itself. Title color must be black.\n",
    "+ Respectively\n",
    "    - Username\n",
    "    - Display Name\n",
    "    - Phone\n",
    "    - Email\n",
    "    - User Roles\n",
    "    \n",
    "should include their labels. On the right side of each of them, there should be textboxes for the user to log in.\n",
    "+ There should be \"Enabled:\" label and checkbox just below them.\n",
    "+ On the right side, there should be a dropdown menu where user roles are assigned. This dropdown menu should include:\n",
    "    - Guest\n",
    "    - Admin\n",
    "    - SuperAdmin"
   ],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "source": [
    "![Photo](https://www.htk.org.tr/content/upload/companies/pi-works-logo-solid-bars--20181119154628.png)\n"
   ],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ]
}