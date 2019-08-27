# OperacionesCalc
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Aplicacion02
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void btnSumar_Click(object sender, EventArgs e)
        {
            // Sumar dos numero
             double nro1, nro2, suma;
            // Leer nro1 y nro 2
             nro1 = double.Parse(txtNro1.Text);
             nro2 = double.Parse(txtNro2.Text);
            //Sumar los numeros
             suma = nro1 + nro2;
            //Escribir la suma
             MessageBox.Show("La suma es: " + suma);
        }

        private void btnSumar_Click(object sender, EventArgs e)
        {
            // Restar dos numeros
            double nro1, nro2, restar;
            // Leer nro1 y nro 2
            nro1 = double.Parse(txtNro1.Text);
            nro2 = double.Parse(txtNro2.Text);
            //Restar los numeros
            restar = nro1 + nro2;
            //Escribir la suma
            MessageBox.Show("La resta es: " + restar);
        }

        private void btnSumar_Click(object sender, EventArgs e)
        {
            // Multiplicar dos numeros
            double nro1, nro2, Multiplicacion;
            // Leer nro1 y nro 2
            nro1 = double.Parse(txtNro1.Text);
            nro2 = double.Parse(txtNro2.Text);
            //Multiplicar los numeros
            Multiplicacion = nro1 + nro2;
            //Escribir la suma
            MessageBox.Show("La Multiplicacion es: " + Multiplicacion);
        }

        private void btnSumar_Click(object sender, EventArgs e)
        {
            // Dividir dos numero
            double nro1, nro2, Dividir;
            // Leer nro1 y nro 2
            nro1 = double.Parse(txtNro1.Text);
            nro2 = double.Parse(txtNro2.Text);
            //Dividir los numeros
            Dividir = nro1 + nro2;
            //Escribir la Division
            MessageBox.Show("La Division es: " + Dividir);
        }

        private void btnSumar_Click(object sender, EventArgs e)
        {
            //Salir del Formulario
            Close();
        }
        
        private void btnSumar_Click(object sender, EventArgs e)
        {
            // Llamar al formulario ayuda
            frmAyuda frm
        }
    }
}
