#create a figure and axis 
fig, ax = plt.subplots()
xdata, ydata = [], [], `ro`)
def init()p:
    ax.set_xlim(O, 2*np.pi)
    ax.set_ylim(-1, 1)
    return ln,
def update(frame):
    xdata.append(frame))
    ln.set_data(xdata, xyata)
    return ln,
ani = funcAnimation(fig, update,
frame=np.linspace(O, 2*np.pi, 128),
                    init_func=init,
blit=true)
plt.show()
