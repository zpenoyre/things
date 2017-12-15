# things
the number of things in the universe
__________________________________________
IMPORTANT THING 1

Here's the function to save the data in the right format:

    footerText='/NameInLegend/Colour/Linsetyle/'
    np.savetxt('fileName.txt',data,fmt='%1.3e \t',header='M (M_s) \t dN/dMdV (M_s^-1 pc^-3)',footer=footerText)
      
__________________________________________

The ipynb will automatically plot your data, label it with the 'NameInLegend', give it your specified 'Colour' and plot it with the specified 'linestyle'.

At the moment you cannot use LaTeX in 'NameInLegend', if this is a problem let me know and I'll think about a workaround
The 'colour' should be a hex string, I like to get mine from here: https://coolors.co/browser
The 'linestyle' is normal matplotlib linestyle ('-' is straight, '--' is dashed, ':' is dotted)

Feel free to upload you data and run the notebook to see how it looks BUT
__________________________________________
IMPORTANT THING 2

Please do not make pull requests with changes to the notebook, just with your data added.
__________________________________________

Here's where the document's living on Overleaf (https://www.overleaf.com/12813067jrqsbbzcgdsg#/48923716/)

Happy hunting!
