# OddAndEvenDigits
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace odd_and_even
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {
            int number;
        }

        private void Form1_Load(object sender, EventArgs e)
        {
            int number, remainderOfnumber;
        }

        private void label5_Click(object sender, EventArgs e)
        {
            
        }

        private void label3_Click(object sender, EventArgs e)
        {

        }

        private void button1_Click(object sender, EventArgs e)
        {
            int remainderOfnumber = 0;
            int number = 0;

            remainderOfnumber = number % 2;

            if (remainderOfnumber == 0)
            {
                label5.Text = "this is an even number";
            }
            else
            {
                label5.Text = "this is an odd number";
            }
        }
    }
}


