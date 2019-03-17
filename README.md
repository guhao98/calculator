import java.awt.*;
import java.awt.event.*;
import javax.swing.*;

public class calculator extends Frame implements ActionListener, WindowListener
{
    private Container container;
    private GridBagLayout layout;
    private GridBagConstraints constraints; 
    private JTextField displayField;         //计算结果显示区
    private String lastCommand;           //保存+,-,*,/,=命令0
    private double result;               //保存计算结果
    private boolean start;           //判断是否为数字的开始
    private JMenuBar menubar;
    private JMenuItem m_exit;
    private JMenuItem m2_ejz;
    private JMenuItem m2_bjz;
    private Dialog dialog;
    private Label label_dialog;
    private JButton button_sqrt;
    private JButton button_plusminus;
    private JButton button_CE;
    private JButton button_cancel;
    private JButton button_1;
    private JButton button_2;
    private JButton button_3;
    private JButton button_4;
    private JButton button_5;
    private JButton button_6;
    private JButton button_7;
    private JButton button_8;
    private JButton button_9;
    private JButton button_0;
    private JButton button_plus;
    private JButton button_minus;
    private JButton button_multiply;
    private JButton button_divide;
    private JButton button_point;
    private JButton button_equal;
    private JButton button_log;
    private JButton button_tan;
    private JButton button_cos;
    private JButton button_sin;
    private JButton button_exp;
